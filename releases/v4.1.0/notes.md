# Sromoto 4.1.0

Bu orta ölçekli güncelleme, kervan hazırlığı ve rota oluşturma iş akışlarını genişletir; Bot ile Manager'ın yerinde güncellenmesini iyileştirir.

- Meslek ekranına script oluşturma ve mevcut scriptleri düzenleme eklendi. Ticaret ve hırsız teslim rotaları, komut adımlarıyla birlikte kaydedilebilir; adımlar eklenebilir, silinebilir ve yeniden sıralanabilir.
- Hırsız teslimi için rota çizimi desteklendi. Teslim noktasında petten inme ve bekleme adımları kullanılabilir; şehir geçişleri rota verisinde ayrı olaylar olarak ele alınır.
- Kervan mal adedi dört haneli girilebilir. Seçilen miktara göre yıldız tahmini arayüzde güncellenir; nihai mal ve yıldız durumu sunucu yanıtıyla doğrulanır.
- Envanter doluluk ve stok denetimleri düzeltildi. Depo slotları karakter çantasına eklenmez; çanta boşaltılıp yeniden bağlanıldığında durum yeniden okunur. Yetersiz Pill/Recovery veya dolu çantayla otomatik alım ve kervan başlangıcı güvenli biçimde bekletilir.
- Binek kaybından sonra farklı başlangıç şehrinde yeni kervan hazırlanması ve kayıtlı rota durumunun yeniden değerlendirilmesi iyileştirildi.
- Bot ve Manager'ın hesap, ayar, rota ve oturum verileri çalıştırıldıkları klasörün `data` dizininde tutulur. Eski AppData kayıtları silinmeden taşınır; hesap şifreleri düz metin olarak kopyalanmaz.
- Güncelleyici Bot ve Manager'ı aynı kurulum klasörüne yerleştirir ve eksik/eski Manager dosyasını onarır. Her iki uygulama da çıkışta onay ister.

Not: Emülatörden canlı rota yakalama, Windows'ta uygun paket yakalama sürücüsü ve izinleri gerektirir. Canlı oyun sunucusundaki rota, ışınlanma ve kervan işlemleri sunucu onayıyla yürütülür.
