# Sromoto 3.0.7

Bu yama 3.0.6'da giriş tamamlandıktan sonra Genel Bakış ekranı açılırken oluşan hatayı düzeltir.

## Düzeltme

- Arayüzün bölge ve koordinat listeleri, yeni ortak Travel navigator'üne yönlendirilir. Eski `controller.navigation` erişimi artık `AttributeError` oluşturmaz.
- Yayın iş akışı, giriş sonrası paneli sunucu bağlantısı olmadan açıp yenileyen bir kontrol çalıştırır; benzer arayüz-bağımlılık hatalarında paket yayınlanmaz.
- Modüllerin ters sırayla yüklenmesinde oluşabilen döngüsel import düzeltildi; yayın iş akışı bu sırayı da kontrol eder.

Not: Savaş sırasında ışınlanma kurtarmasının canlı oyun doğrulaması 3.0.6 ile aynı şekilde beklemektedir.
