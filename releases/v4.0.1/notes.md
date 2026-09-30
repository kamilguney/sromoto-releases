# Sromoto 4.0.1

Bu sürüm, güncelleme sonrasında bot ve Manager dosyalarının ayrı bir sürüm klasöründe kaybolmuş gibi görünmesi sorununu giderir.

- Yeni güncelleyici, imzalı paketi botun çalıştırıldığı klasöre kurar. `Sromoto.exe` ve `SromotoManager.exe` aynı klasörde kalır.
- Kurulum, çalışan bot ve Manager örneklerini kontrol eder; açık başka bir örnek varsa mevcut dosyalara dokunmadan durur.
- Eski uygulama dosyaları geri alınabilir yedeğe taşınır. Yeni sürüm açılış doğrulaması başarısız olursa dosyalar geri yüklenir.
- Paket açılırken ve kurulum sonrasında iki EXE'nin varlığı; yeni yayınlarda ikisinin de imzalı özeti doğrulanır.

Geçiş notu: 4.0.0'ın kendi güncelleyicisi 4.0.1'i ilk seferde eski sürümlü kurulum konumuna yerleştirir. Yerinde kurulum davranışı 4.0.1'den sonraki otomatik güncellemelerde veya 4.0.1 paketinin tercih edilen bot klasörüne elle açılmasıyla etkinleşir.
