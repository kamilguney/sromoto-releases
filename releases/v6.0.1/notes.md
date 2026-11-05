# Sromoto 6.0.1 — Kurulum ve Güncelleme SSL Düzeltmesi

Oyun sürümü: `2.0.7.5.127-ec5802a`.

- Kurulum, Bot ve Manager güncelleme bağlantıları Windows sertifika deposu ve yerel sertifika zinciri doğrulamasıyla açılır. Eksik ara sertifikalar veya Windows’a güvenilen yayıncılar nedeniyle oluşan `CERTIFICATE_VERIFY_FAILED / unable to get issuer certificate` hatası giderildi.
- TLS sertifika ve sunucu adı doğrulaması korunur; güvenilmeyen bağlantıya doğrulamasız tekrar denenmez. İmzalı manifest, dosya özeti ve indirme sınırı kontrolleri korunur.
- Windows sertifika altyapısı üç çalıştırılabilir dosyaya da eklenir ve paket açılış kontrollerinde yüklenmesi doğrulanır.

Eski kurulum aracı bu hatayı veriyorsa bu sürümün **SromotoSetup.exe** dosyasını tarayıcıyla indirip çalıştırın. Mevcut Sromoto klasörünü seçin; kullanıcı verileri korunur. Bilgisayarda gerçekten güvenilmeyen bir sertifika varsa bağlantı reddedilmeye devam eder.
