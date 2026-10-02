# Sromoto 4.0.2

Bu sürüm, oyunun `2.0.1.5.103-66d97a1` güncellemesiyle uyumluluğu ve çok karakterli hesaplarda giriş doğruluğunu iyileştirir.

- Güncel kimlik ve gateway sürüm bilgileri kullanılır; gateway isteğindeki oturum belirteci her girişte yenilenir.
- Birden fazla karakterli hesaplarda seçim, sunucunun beklediği karakter listesi sırasına göre yapılır. Girişte seçilen karakterin kimliği doğrulanır; başka karakterin envanteri gösterilmez.
- Karakter adı belirtilmemişse seçim penceresi açılır. Seçilen karakter hatırlanır ve bot içinden karakter değiştirilebilir.
- Şehir ve kanal geçişlerinde artık kullanılmayan sahne onay paketi beklenmez; geçiş sunucunun sahne ve konum verisiyle doğrulanır.
- Meslek bilgisi bulunmayan karakterlerde giriş, meslek sorgusuna bağlı kalmaz. Kervan kontrolleri yalnız kervan akışında yapılır.
- Hareket göndericisinin yeniden bağlantı sonrası durması ve Manager durum dosyasındaki geçici Windows kilitleri için kurtarma eklendi.
- Bot ve Manager hesap kayıtları ortaklaşır; Manager güncelleme bildirimini gösterir. Kapatma ve sistem tepsisine küçültme davranışları düzenlendi.

Not: Canlı oyun sunucusunun yanıtları ve kervan rotaları ortama göre değişebilir; kritik işlemler sunucu onayıyla yürütülmeye devam eder.
