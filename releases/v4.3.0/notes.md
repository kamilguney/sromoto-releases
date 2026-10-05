# Sromoto 4.3.0

Bu sürüm, Bot ve Manager'ın kurulum/güncelleme akışını yeniler ve Manager'daki çoklu hesap takibini genişletir.

- **Bu sürüme geçişte temiz uygulama kurulumu:** Yayın sayfasından `SromotoSetup.exe` indirin. Açık Bot ve Manager pencerelerini kapatın, Setup'ta Bot'u kullandığınız gerçek klasörü seçin. İmzalı paket doğrulandıktan sonra Bot ve Manager aynı klasörde yeniden kurulur; `data/` içindeki hesap, rota ve loglar korunur. İsterseniz boş bir klasör seçerek yeni kurulum da yapabilirsiniz; eski klasörünüzdeki `data/` bu durumda kendiliğinden taşınmaz.
- Manager'ın zil menüsüne **Güncellemeyi Başlat** eklendi. Yeni sürümleri Bot'u açmadan sorgulayabilir; çalışan Bot'ları kapattıktan sonra imzalı paketi Manager üzerinden de kurabilirsiniz.
- Manager'da **Tüm kapalı hesapları aç** düğmesi, çalışan hesapları atlayarak kayıtlı kapalı hesaplar için ayrı Bot pencereleri açar. Aynı hesaptaki birden fazla karakter kaydı tek kez başlatılır.
- Aktif botlarda Gold altında oturumun ilk doğrulanmış bakiyesine göre net değişim gösterilir. Bu değer alış ve harcamaları da içerir; kesin ticaret kârı değildir.
- Kullanıcıya görünen Gold tutarları standart K/M/B ölçeğine geçti: 100.000 = 100K, 1.000.000 = 1M, 1.000.000.000 = 1B.
- Güncelleme paketi hazır `clientless_v3/routes` rotalarını da içerir. Eski sürümden kalan, değiştirilmemiş `data/routes` kopyaları artık yeni paket rotasını gölgelemez. Kişisel rotalar ve düzenleme yedekleri silinmez ya da herkese açık pakete konulmaz.

Otomatik testler çalıştırıldı. İlk temiz kurulumun gerçek Windows EXE ve canlı hesap verileriyle son kullanıcı doğrulaması ayrıca yapılmalıdır.
