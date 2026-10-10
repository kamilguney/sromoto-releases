# Sromoto 4.3.2

Bu bakım sürümü, oto kervanda yeniden bağlantı ve hareket kurtarmasını iyileştirir.

- Karakter seçildikten sonra sahne onayı için üst bekleme sınırı 35 saniyeye çıkarıldı; paket erken gelirse giriş hemen devam eder.
- Yeniden bağlantıda binek/mal durumu sunucudan tekrar doğrulanır. Bineğe binme reddedilirse en fazla bir güvenli tekrar yapılır.
- Mal alımı 1150 koduyla reddedildiğinde çanta, altın ve stoklar yeniden doğrulanmadan ikinci alım yapılmaz.
- Yüklü kervan aynı yürüyüş hedefine takılırsa bağlı navmesh üzerinde engeli dolaşan yol sınırlı sayıda denenir; aynı komut iki dakika boyunca körlemesine tekrarlanmaz.
- Başlangıç NPC'sine dönüşte karakter gerçekten ilerlediyse eski yürüyüş takılma sayacı sıfırlanır.
- Ölüm sonrası şehre dönüş reddedilirse en fazla üç kontrollü deneme yapılır; canlanma ve yeni konum doğrulanmadan rota sürdürülmez.

Otomatik testler geçti. Sunucuya ve canlı kervanlara bağlı davranışların oyun içinde ayrıca doğrulanması gerekir. Süreli toplayıcı petin envantere eklediği slotlar bu sürümde çözümlenmedi; belirsiz kapasitede otomatik alım güvenlik nedeniyle ertelenmeye devam eder.
