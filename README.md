# ESC-50 Ses Verisi Analizi Projesi  

Bu proje, **ESC-50** veri setini kullanarak çevresel seslerin analizi ve sınıflandırılması üzerine odaklanmaktadır. Projede, ses özelliklerinin çıkarılması, boyut indirgeme (Dimensionality Reduction), kümeleme (Clustering) teknikleri ve basit bir sınıflandırma modeli geliştirilmesi adım adım uygulanmıştır.  

Proje, **librosa** ve **scikit-learn** gibi güçlü Python kütüphanelerini kullanarak ses verilerinden anlamlı bilgiler elde etmeyi ve her aşamada görselleştirme ile sonuçları daha anlaşılır hale getirmeyi amaçlamaktadır.  

---

## 🧠 Proje Kapsamı  

1. **Veri Yükleme ve Ön İşleme**  
   - Büyük ses veri setleri ile çalışma.  
   - Harici kaynaklardan dinamik veri indirme.  

2. **Ses Özelliklerinin Çıkarılması**  
   - **MFCCs**, **Chroma Features**, **Spectral Contrast** gibi temel ses özellikleri.  
   - **librosa** ile özellik çıkarımı.  

3. **Boyut İndirgeme ve Görselleştirme**  
   - **PCA** ve **t-SNE** teknikleri ile veriyi 2D/3D uzayda görselleştirme.  
   - Gizli desenleri anlamayı kolaylaştırma.  

4. **Kümeleme (Clustering)**  
   - **K-Means**, **DBSCAN**, **Agglomerative Clustering**, **Gaussian Mixture Models**, **HDBSCAN** algoritmalarının uygulanması.  
   - Doğal grupları keşfetme.  

5. **Basit Sınıflandırma Modeli**  
   - **Logistic Regression** ile çevresel seslerin sınıflandırılması.  
   - Model doğruluğunun değerlendirilmesi.  

---

## 🛠 Kullanılan Teknolojiler ve Araçlar  

- **Python 3.11+**  
- **Jupyter Notebook**  
- **pandas**, **numpy**  
- **librosa** – Ses analizi ve özellik çıkarımı  
- **requests**, **os** – Dosya yönetimi ve indirme  
- **matplotlib**, **seaborn** – Veri görselleştirme  
- **scikit-learn** – Kümeleme, sınıflandırma, boyut indirgeme  
- **KMeans**, **DBSCAN**, **AgglomerativeClustering**, **HDBSCAN** – Kümeleme algoritmaları  
- **PCA**, **TSNE** – Boyut indirgeme yöntemleri  
- **LogisticRegression** – Sınıflandırma modeli  
- **LabelEncoder**, **StandardScaler** – Veri ön işleme  
- **ESC-50 Dataset** – Kullanılan ses veri seti  

---

## 📊 Proje Özellikleri  

- Veri toplama → Özellik çıkarımı → Kümeleme & boyut indirgeme → Sınıflandırma adımlarını içeren uçtan uca çözüm.  
- **Denetimsiz öğrenme** (unsupervised learning) tekniklerinin uygulanması.  
- Her aşamada görselleştirme ile veri analizi.  

---

## 🎯 Uygulama Alanları  

- **Akıllı gözetim sistemleri** – Olağandışı ses olaylarının tespiti.  
- **Ses manzarası analizi** – Şehir veya doğal ortam ses kompozisyonunun incelenmesi.  
- **Sesli asistan geliştirme** – Ortam seslerini daha iyi tanıma.  
- **Akademik araştırmalar** – Ses verisi analizi üzerine çalışma örneği.  

---

## 🔬 Metodoloji  

1. Veri toplama  
2. Ses özelliklerini çıkarma  
3. Kümeleme ve boyut indirgeme  
4. Sınıflandırma modeli geliştirme  
5. Model performans değerlendirmesi  

---

## 💡 Yenilik ve Farklılık  

- Ses sinyali işleme tekniklerinin modern makine öğrenmesi yöntemleri ile entegrasyonu.  
- Karmaşık verilerin kolay anlaşılması için gelişmiş görselleştirmeler.  

---

## 🚀 Gelecek Geliştirmeler  

- Derin öğrenme (Deep Learning) modelleri ile sınıflandırma.  
- Daha büyük ve çeşitli ses veri setlerinin entegrasyonu.  
- Gerçek zamanlı ses
