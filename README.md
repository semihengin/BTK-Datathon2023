# BTK Datathon 2023 - Müşteri Sınıflandırma Projesi

Bu proje, BTK Akademi, Google ve Girişimcilik Vakfı iş birliğiyle düzenlenen **BTK Datathon 2023** kapsamında geliştirilmiştir. Amaç, bir e-ticaret firmasının müşterilerini belirli segmentlere ayırarak, hedef odaklı pazarlama stratejileri geliştirmeye yönelik bir makine öğrenmesi modelini oluşturmaktır.

## 🚀 Proje Amacı

Bu projede, bir e-ticaret platformunun müşterilerini demografik ve davranışsal verilerine göre sınıflandırmak hedeflenmiştir. Sınıflandırma modeli ile firmalar, belirli müşteri gruplarına özel pazarlama stratejileri geliştirebilir, kampanya yönetimlerini optimize edebilir.

## 📊 Veri Seti

Proje kapsamında kullanılan veri seti, aşağıdaki özellikleri içermektedir:

- **Cinsiyet**
- **Yaş Grubu**
- **Medeni Durum**
- **Eğitim Düzeyi**
- **İstihdam Durumu**
- **Yıllık Ortalama Gelir**
- **Yaşadığı Şehir**
- **En Çok İlgilendiği Ürün Grubu**
- **Yıllık Ortalama Satın Alım Miktarı**
- **Yıllık Ortalama Sipariş Verilen Ürün Adedi**
- **Eğitime Devam Etme Durumu**
- **Yıllık Ortalama Sepete Atılan Ürün Adedi**
- **Müşteri Segmenti (Hedef Değişken)**

## 🛠 Kullanılan Teknolojiler

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 📌 Uygulanan Adımlar

1. **Keşfisel Veri Analizi (EDA)**: Verinin genel yapısı incelenmiş, eksik veriler analiz edilmiştir.
2. **Veri Ön İşleme**: Eksik veriler doldurulmuş, kategorik değişkenler dönüştürülmüştür.
3. **Modelleme**: Çeşitli makine öğrenmesi algoritmaları uygulanarak en iyi performans gösteren model seçilmiştir.
   
## 📂 Proje Dosyaları

- **`main.ipynb`** - Veri analizi, ön işleme ve modelleme adımlarını içeren Jupyter Notebook dosyası.
- **`train.csv`** - Modelin eğitildiği veri seti.
- **`test_x.csv`** - Test veri seti.
- **`README.md`** - Proje hakkında bilgiler içeren bu dosya.

---

**Not:** Bu proje **BTK Datathon 2023** kapsamında geliştirilmiştir. Yarışma hakkında detaylı bilgi almak için [BTK Akademi](https://www.btkakademi.gov.tr/portal/public/Datathon2023) sayfasını ziyaret edebilirsiniz.
