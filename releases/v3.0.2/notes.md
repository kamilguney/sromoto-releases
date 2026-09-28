# Sromoto 3.0.2

Bu sürüm, Oto Kervan hazırlığını ve bağlantı sonrası toparlanmayı iyileştirir. Oyun sunucusundaki davranışın canlı doğrulaması sürüm paketinin dışında yapılmalıdır.

## İyileştirmeler

- Oto Kervan mal seçiminde başlangıç şehrinin Özel Malı varsayılan gelir.
- Desteklenen otomasyon seçenekleri ilk kullanımda işaretlidir; önceden kaydedilen kullanıcı tercihleri korunur.
- Binek Recovery potunun kullanım eşiği varsayılan %60'tır ve arayüzden %1–%99 arasında ayarlanıp hatırlanır.
- Rota adım sayacı arayüzde tek tek ilerler; yalnız gösterimi değiştirir, hareket paketlerini veya binek hızını etkilemez.
- Kanal bilgisi “Mevcut Kanal” olarak adlandırılır. Pencere başlığının altındaki Sromoto menü satırı kaldırıldı; güncelleme kontrolleri alt çubuğa taşındı.

## Hata düzeltmeleri

- İlk dünya girişindeki karakter envanteri paketi pot stoklarını besler. Kısmen çözümlenebilen çantalarda doğrulanmış pot yığınları “En az … adet” olarak gösterilir ve kullanılabilir; kesin olmayan toplam stok olarak sunulmaz.
- Bağlantı kopup yeniden açıldığında aktif kervan sunucudaki binek ve mal durumunu tekrar sorgular; binek yalnız sunucu durumu gerektiriyorsa yeniden binilir ve rota mevcut konumdan sürdürülür.
- Sunucu kervan sorgusunda meslek modunun etkin olmadığını bildirirse, otomatik başlangıç sırasında meslek modu en fazla bir kez kapatılıp yeniden etkinleştirilerek durum tekrar doğrulanır.
- Güncelleme bildirimi özel kaynak depo yerine açık, imzalı dağıtım deposunu kullanır.

Not: Bağlantı/kervan/pot akışlarının canlı oyun uçtan uca doğrulaması bu sürümün sözdizimi ve paket kontrolünden ayrıdır. İmzasız veya doğrulanmamış paket kurulmaz.
