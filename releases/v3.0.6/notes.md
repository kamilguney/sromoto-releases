# Sromoto 3.0.6

Bu sürüm seyahat işlemlerini ortak bir katmanda toplar ve savaş sırasında kesilen ışınlanmaların toparlanmasını iyileştirir.

## İyileştirmeler

- Manuel seyahat, takip ve Oto Kervan, yürüyüş/kanal/bölge/ışınlanma için ortak Travel katmanını kullanır. Oyun içi canlı trafikten kaydedilmiş kervan rota adımları yeniden çizilmez.
- Çağrılmış taşıma bineğiyle hızlı şehir ışınlanması gönderilmez; uygun kervan kapısı kullanılır. Binek yoksa başlangıç şehrine dönüşte doğrulanmış şehir içi hızlı ışınlanma, ardından kapıya navmesh yaklaşımı denenir.
- Kendi karakterine ait canlı HP düşüşü veya sunucunun `1080` savaş reddi görülürse, bineksiz seyahat ulaşılabilir ve görünen moblardan uzak bir noktaya ilerleyip ışınlanmayı yeniden dener. Ulaşılamayan noktalara kör hareket isteği gönderilmez.
- Karakterin kimliği, temel durum özeti ve doğrulanmış HP bildirimleri bağımsız Character katmanında tutulur.
- Kaynak yayın paketi yeni Character ve Travel modüllerini içerir.

Not: MP paket alanı henüz doğrulanmadığı için saldırı tespitinde kullanılmaz. Savaş altında ışınlanma ve binek ölümü sonrası dönüş canlı oyun oturumunda henüz uçtan uca doğrulanmadı.
