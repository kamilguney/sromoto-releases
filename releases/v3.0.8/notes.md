# Sromoto 3.0.8

Bu sürüm karakter ve meslek ekranlarını genişletir; mağara geçişleri ile seyahat hareketini iyileştirir.

## İyileştirmeler ve düzeltmeler

- Karakter ekranında doğrulanmış HP, Mana ve EXP çubukları ile sanal bakiyeler gösterilir. Bilinen indeksler Silk, Elmas, beceri ve guild puanı olarak adlandırılır.
- Meslek Değiştir sekmesinde hedef meslek ve rumuz karaktere özel kaydedilir. Otomasyon, mevcut meslek verisi eksikse bile kayıtlı hedefi kontrollü dener; sunucu yanıtı ve bekleme nedeni ekranda görünür. Manuel “Şimdi Değiştir” düğmesi kaldırıldı.
- Meslek değiştirme isteği `0xFB4E`/`0xB1AD` ile gönderilir ve yeni meslek ancak sunucu verisiyle doğrulanınca başarılı sayılır. `1131` reddinde uygulamanın uydurduğu 600 saniyelik ara kaldırıldı; açık otomasyon yanıt tamamlandıktan sonra en erken bir saniyede yeniden dener. Bu, sunucunun reddini aşma garantisi değildir.
- Meslek ekranı açıldığında güncel durum sorgulanır; meslek kapalıyken kervan alanları bekleme yerine daha anlaşılır boş değerler gösterir.
- Donwhang Mağarası kat geçişleri, kapı seçimi ve navmesh yaklaşımı iyileştirilir. Yürüyüşte ilerleme yoksa alternatif yol denenir; seyahat açıklamaları hedefe göre netleştirilir.
- Girişteki `0x4C25` ve karakter güncellemelerinde seçili karakterin meslek/binek durumunun yanlış oyuncuya bağlanması engellenir.

Not: Mağara kapıları, meslek değişimi ve saniyelik yeniden deneme canlı oyun oturumunda uçtan uca doğrulanmadı. Sunucunun `1131` yanıtı kalan süreyi bildirmediğinden gerçek bekleme süresi bu koddan hesaplanamaz.
