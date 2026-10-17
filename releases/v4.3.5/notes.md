# Sromoto 4.3.5

Bu sürüm, kervan kurtarmasını, Manager'dan yıldız seçimini ve otomatik güncelleme akışını iyileştirir.

- Kervan bineği tek başına ölürse karakterin canlanması beklenmeden başlangıç şehrine dönülür; karakter de ölürse önce öldüğü şehirde canlanması doğrulanır. Ardından meslek, binek ve mal sunucu yanıtlarıyla yeniden hazırlanır.
- Binek hareketi sunucuda ilerlemiyorsa daha düşük hızla kontrollü yeniden deneme yapılır; iki alternatif yol da başarısızsa teşhis bilgisi korunur.
- Manager'dan kervan başlatırken 1–5 yıldız seçilebilir. Her bot seçilen yıldızın mal miktarını kendi bineğinin doğrulanmış kapasitesinden hesaplar; desteklenmeyen seçim reddedilir.
- Bot ve Manager imzalı güncellemeyi arka planda indirir, oyun oturumu ve aynı kurulumdaki diğer süreçler kapandığında otomatik kurar ve başlatan uygulamayı yeniden açar. Bu davranış bildirim menüsünden kapatılabilir.
- Başarılı kurulumdan sonra yalnız son geri alma yedeği tutulur; doğrulanmış eski kurulum artıkları ve indirme önbelleği temizlenirken kullanıcı verileri korunur.

Yayın kapıları Windows üzerinde 222 V3/Manager testi, 8 harita testi, sözdizimi ve giriş sonrası GUI açılış kontrolüyle doğrulandı. Canlı kervan ve otomatik kurulum davranışı kullanıcı ortamında ayrıca izlenmelidir. Önceki EXE sürümleri yeni otomatik kurulum kodunu içermediğinden 4.3.5'e ilk geçiş için mevcut Setup veya elle kurulum gerekebilir.
