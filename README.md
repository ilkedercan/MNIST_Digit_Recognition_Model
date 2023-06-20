# MNIST_Digit_Recognition_Model
# MNIST Sayı Tanıma Modeli

Bu proje, MNIST veri seti üzerinde sayı tanıma için bir model geliştirmeyi amaçlamaktadır. Proje, Evrişimli Sinir Ağı (Convolutional Neural Network, CNN) yöntemini kullanarak, sayıları doğru bir şekilde tanımak için bir öğrenme modeli oluşturmaktadır.

## İsim: İlke Dercan
## Model Yöntemi: Evrişimli Sinir Ağı (Convolutional Neural Network, CNN)

### Veri Seti

Kullandığımız veri seti, MNIST veri setidir. Bu veri seti, 60.000 eğitim örneği ve 10.000 test örneği içeren el yazısı sayı görüntülerinden oluşmaktadır. Her bir görüntü 28x28 pikselden oluşur.

### Model

Projede, Evrişimli Sinir Ağı (CNN) modeli kullanılmıştır. Bu model, evrişim katmanları ve havuzlama (pooling) katmanları gibi özel katmanlar kullanarak görüntü verilerinden özellikler çıkarır ve sayıları tanımak için kullanılır.

Modelin yapısal bilgileri:

- Evrişim katmanları
- Havuzlama katmanları
- Tam bağlantılı (fully connected) katmanlar
- Aktivasyon fonksiyonları  

### Eğitim

Model eğitimi için MNIST veri setinin eğitim bölümü kullanılmıştır. Eğitim sürecinde, 5 epoch (döngü) kullanılmıştır ve her bir batch'te 16 örnek işlenmiştir. Eğitim sürecinde elde edilen sonuçlar doğrulama bölümünde değerlendirilmiştir.

### Sonuçlar

Eğitim süreci sonucunda elde edilen doğruluk oranı ve kayıp değerleri aşağıdaki gibidir:

- Eğitim Doğruluğu: XX%
- Eğitim Kaybı: XX
- Doğrulama Doğruluğu: XX%
- Doğrulama Kaybı: XX
