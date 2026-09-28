# Sromoto 3.0.4

Bu sürüm kervan bağlantı kopması sonrası devam akışını ve sistem tepsisi bilgisini iyileştirir.

## Düzeltmeler ve iyileştirmeler

- Oto Kervan Başlat, başlangıç şehrine dönüş veya ışınlanma istemeden önce sunucudaki mevcut binek, mal ve kervan aşamasını sorgular. Aktif yüklü binek doğrulanırsa mevcut şehir/konumdan seçili rotaya devam eder.
- Bağlantı kopması sırasında rota yürüyüşü sonlansa bile devam isteği korunur; tekrar bağlanınca sunucu durumu yeniden doğrulanır.
- Seçili rota, mal, tekrar yönü ve son rota adımı karaktere özel küçük bir kayıt olarak saklanır. Uygulama yeniden açıldığında yalnızca sunucuda aktif binek ve mal doğrulanırsa rota sürdürülür; kayıt tek başına hareket başlatmaz.
- **Durdur** otomatik devamı kapatır. Uygulamayı kapatmak seçili rota kaydını silmez.
- Sistem tepsisi simgesinin açıklaması pencere başlığıyla birlikte hesap ve karakter adını gösterir.

Not: Kervan devamı canlı bağlantı/kopma senaryosunda henüz uçtan uca doğrulanmadı. Sunucu kervanı veya güncel konum doğrulanamazsa otomatik hareket başlatılmaz.
