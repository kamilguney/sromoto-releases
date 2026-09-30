# Sromoto 3.0.9

Bu sürüm Oto Kervan'ın ticaret süresi veya binek kaybı sonrasında başlangıç şehrine dönüşünü iyileştirir.

## Düzeltmeler

- Sunucudan bildirilen ticaret süresi bitmişse binek artık aktif sayılmaz. Bineksiz dönüşte kervan kapısı yerine uygun şehir kapısı seçilir.
- Seçilen dönüş kapısına bağlı bir navmesh yolu bulunamaz veya yaklaşım doğrulanamazsa, erişilemeyen kapı elenip alternatif kapı aranır. Karakter ölümü gibi farklı hatalar bu yolla gizlenmez.
- Kervan rotasında 20 saniye ilerleme görülmezse sunucudaki kervan süresi, binek ve mal durumu yeniden sorgulanır. Süre bitmiş, binek kaybolmuş veya mal tükenmişse ilgili hazırlık sürecine dönülür.
- Donwhang'dan Jangan'a dönüşte yanlış kapı seçimindeki koordinatlar için çevrimdışı regresyon testleri eklendi.

Not: Düzeltmeler çevrimdışı testlerden geçti; ticaret süresi bitimi ve binek ölümü sonrası dönüş canlı oyun oturumunda henüz uçtan uca doğrulanmadı.
