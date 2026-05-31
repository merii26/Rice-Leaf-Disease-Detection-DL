# 🌾 Çeltik (Pirinç) Yaprağı Hastalık Tespiti - Derin Öğrenme Projesi

Bu proje, pirinç yapraklarındaki hastalıkları görüntü işleme ve derin öğrenme teknikleri kullanarak otomatik olarak tespit etmeyi amaçlayan bir yapay zeka modelidir.

## 🚀 Proje Hakkında
Tarım sektöründe bitki hastalıklarının erken teşhisi, mahsul kaybını önlemek için kritik öneme sahiptir. Bu projede, **MobileNetV2** transfer öğrenme (transfer learning) mimarisi kullanılarak hızlı ve yüksek doğruluk oranına sahip bir sınıflandırma modeli geliştirilmiştir.

- **Kullanılan Model:** MobileNetV2 (Hızlı ve hafif mimari)
- **Veri Seti:** Kaggle Rice Leaf Diseases Dataset
- **Sınıf Sayısı:** 6 (5 farklı hastalık + 1 Sağlıklı)

## 🛠️ Kullanılan Teknolojiler
- Python
- TensorFlow / Keras
- OpenCV & NumPy & Matplotlib
- Google Colab (Eğitim ortamı)

## 📁 Proje Yapısı
- `bitki_hastalik_egitim.ipynb`: Veri hazırlama, model mimarisi ve eğitim adımlarını içeren Colab notebook dosyası.
- `test_model.py`: Eğitilmiş modeli kullanarak dışarıdan verilen bir yaprak fotoğrafını test eden script.
- `pirinc_hastalik_modeli.h5`: Eğitilmiş yapay zeka modelinin ağırlıkları.

## ⚙️ Nasıl Çalıştırılır?
1. Repoyu bilgisayarınıza klonlayın:
   `git clone https://github.com/kullaniciadin/Rice-Leaf-Disease-Detection-DL.git`
2. Gerekli kütüphaneleri yükleyin:
   `pip install tensorflow numpy matplotlib`
3. Test dosyasını çalıştırın:
   `python test_model.py`
