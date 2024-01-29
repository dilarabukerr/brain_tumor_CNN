# brain_tumor_CNN

## Kurulum
1. Python için gerekli kütüphaneleri yüklemek için terminale şu komutu yazın: `pip install seaborn`, 'pip install tensorflow'.
2. Verisetine [buradan](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri) ulaşabilirsiniz.

## Transfer Learning
• Transfer Learning: Önceden eğitilmiş EfficientNetB0 modeli kullanılarak transfer
öğrenme uygulanmıştır.
• TensorFlow ve Keras: Modelin oluşturulması, eğitimi ve performans değerlendirmesi
için TensorFlow ve Keras kütüphaneleri kullanılmıştır.
• Optimizasyon: Adam optimizer kullanılarak modelin optimizasyonu sağlanmıştır.
• Geri Çağrılar: TensorBoard, ModelCheckpoint ve ReduceLROnPlateau geri çağrıları,
modelin eğitimi sırasında izleme ve optimizasyon sağlamıştır.

## EfficietNetB0 model
Transfer öğrenme, önceden eğitilmiş büyük veri kümeleri üzerinde başarılı
olan modellerin ağırlıklarını, küçük özel veri kümeleri üzerine aktarma fikrine dayanır. Bu,
küçük veri kümelerinde daha iyi performans elde etmek ve eğitim süresini kısaltmak için
etkili bir yol sunar.
Bu çalışma, önceden eğitilmiş EfficientNetB0 modelini kullanarak transfer öğrenme
prensiplerini benimsemektedir. EfficientNetB0, ImageNet veri kümesinde eğitilmiş
ağırlıklarla yüklenir. Model, eğitim verileri üzerinde belirli bir epoch sayısı için eğitilir.
Optimizasyon amacıyla Adam optimizer kullanılır.


