# brain-tumor-mri-classification
# Brain Tumor MRI Classification

## 📋 Proje Amacı
MRI görüntülerinden beyin tümörü türlerini sınıflandıran derin öğrenme projesi. CNN (Convolutional Neural Network) kullanarak 4 farklı sınıfı ayırt eder.

## 📊 Veri Seti
- **Kaynak:** [Brain Tumor MRI Dataset - Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- **Toplam Görüntü:** 7,022 MRI görüntüsü
- **Sınıflar:** 4 sınıf
  - Glioma: Beyin dokusundan kaynaklanan tümör
  - Meningioma: Beyin zarlarından kaynaklanan tümör  
  - No Tumor: Normal beyin dokusu
  - Pituitary: Hipofiz bezinde oluşan tümör

## 🛠️ Kullanılan Yöntemler

### Model Mimarisi
- **Framework:** TensorFlow/Keras
- **Model Tipi:** Convolutional Neural Network (CNN)
- **Katmanlar:**
  - 3 Convolutional Block (Conv2D + MaxPooling)
  - Dropout katmanları (overfitting önleme)
  - 2 Dense katman

### Veri İşleme
- **Görüntü Boyutu:** 128x128 piksel
- **Data Augmentation:** Rotation, shifting, horizontal flip
- **Normalizasyon:** 0-1 arası ölçeklendirme

### Optimizasyon Teknikleri
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Callbacks:** Early Stopping, Learning Rate Reduction

## 📈 Sonuçlar
- **Test Accuracy:** 85.28%
- **Model Performansı:** Yüksek doğrulukla 4 sınıfı ayırt ediyor
- **Eğitim Süresi:** ~10-15 dakika (GPU ile)

## 📁 Proje Yapısı

## 🔗 Kaggle Notebook
[Brain Tumor MRI Classification - Kaggle Notebook] https://www.kaggle.com/code/helifesen/notebook4e1c9bc838/edit
## 🚀 Kurulum ve Çalıştırma
1. Kaggle hesabı oluşturun
2. Veri setini projenize ekleyin
3. GPU accelerator'ı aktif edin
4. Notebook'u çalıştırın

## 📚 Gereksinimler
- TensorFlow 2.x
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 👨‍💻 Geliştirici
**Akbank Derin Öğrenme Bootcamp Final Projesi**
ilerleyen süreçte beyin tümörü dışındaki hastalıkları da tespit edem bir proje yapmak istiyorum. Ve hazırladığım bu projeyi geliştirmeye devam etmek istiyorum.
