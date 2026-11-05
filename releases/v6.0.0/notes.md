# Sromoto 6.0.0 — Canlı Otomasyon ve Gerçek Minimap

Oyun sürümü: `2.0.7.5.127-ec5802a`.

- Otomatik farm bölgesi karakterin güncel seviyesi ve seçilen yaratık seviye aralığına göre bulunur. Seviye yükseldikçe uygun bölgeye geçilir; Otomasyon için Eğitim Alanı'nda sahne seçmek gerekmez.
- Farm, 1 dışındaki normal kanallarda çalışır; uygun mevcut kanal korunur. Meslek/kervan işlemleri için 1. kanala dönüş doğrulanır.
- Otomasyon seçimleri karaktere özel kaydedilir: rota, ürün, öncelik, hak sınırı, seviye aralığı, yarıçap, kombolar ve yıldız/manuel adet tercihleri yeniden açılışta geri gelir.
- Yeni canlı otomasyon paneli: karakter ve HP/MP/EXP, buff simgeleri ve süreleri, koordinat/bölge/kanal, Dünya süresi ve rezervi, petler ve mevcut farm/kervan durumu.
- Minimap, oyunun orijinal 21 harita görselini ve koordinat tablosunu kullanır. Farm merkezi/yarıçapı ve güncel yaratıklar gösterilir. Ölen/sahneden kaldırılan moblar ayıklanır; eski konum paketleri silinen mobları geri getiremez.
- Eğitimde geçerli yaratık hedefi bitirildikten sonra, filtreye ve sahipliğe uygun düşüşlere aynı yürüme sistemiyle yaklaşılır. Farm sınırı korunur; altın kategori filtresinden bağımsızdır. Çantaya geliş yalnız gerçek sunucu/çanta bildirimleriyle sayılır.
- Kervan bineği ve kapasite bonusu meslek seviyesine göre belirlenir. Güncel oyun içi tabloya göre 1–5 yıldız seçilebilir veya manuel miktar girilebilir; manuel miktarın yıldızı anlık gösterilir. Her yeni yükte güncel sunucu kapasitesi kontrol edilir.
- Envanterde tek tıklama seçer, üzerine gelme eşya bilgisini gösterir, çift tıklama ayrıntılar ve Kuşan/Kullan, Sat, Depoya At/Çantaya Al işlemlerini açar. CTRL ile toplu seçim korunur.
- Menü sırası sadeleştirildi; Karakter Profilleri ve Koşullar menüleri kaldırıldı.

Seçimlerin geri yüklenmesi otomasyonu kendiliğinden başlatmaz. Buff süreleri son sunucu bildiriminden hesaplanır. Toplama yaklaşması yerel testlerle doğrulanmıştır; son canlı test profilinde saldırı becerisi bulunmadığı için gerçek teslim doğrulaması tamamlanamamıştır. İki saatlik kervan hak geçişinin uzun süreli canlı doğrulaması henüz tamamlanmamıştır.
