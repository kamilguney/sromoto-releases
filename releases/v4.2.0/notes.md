# Sromoto 4.2.0

Bu orta sürüm, Bot ve Manager için harita görünümünü ve manuel seyahati genişletir.

- Harita; navmesh üçgenlerini ve sınırlarını, NPC/kapıları, karakterin doğrulanmış konumunu ve hareket/rota durumunu ayrı katmanlarda gösterir. Manager seçilen botun haritasını salt okunur açabilir.
- Bot haritasında çift tıklanan hedefe mevcut seyahat sistemiyle gidilir. Yeni bir hedefe çift tıklanırsa önceki yürüyüş iptal edilir; yalnız son hedef izlenir. Kervan ve mağara katı güvenlik kontrolleri korunur.
- Görünüm çizimleri önbelleğe alınır ve geçersizleşen harita hesapları iptal edilir. Takılma gözlemleri, kullanıcı notlarından ayrı kaydedilir; navmesh verisi değiştirilmez.
- Bir metrelik yol ızgarasında görünmeyen dar geçitler için gerçek navmesh üçgenleri üzerinde ikinci yol araması yapılır. Gerçekte bağlantısız alanlar hâlâ reddedilir.
- Karakter ve Manager altın göstergesi girişteki sabit miktar yerine canlı envanter güncellemesini kullanır.
- Bot ve Manager Windows paketindeki ayrı EXE'ler olarak kalır; ikisinin de harita çalışma verileri paket öz-denetiminde doğrulanır.

Yerel otomatik testler çalıştırıldı. Canlı oyun ve yayımlanmış Windows paketindeki hareket davranışı ayrıca gözlemlenmelidir.
