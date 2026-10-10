# Sromoto 4.3.3

Bu yama, eski kayıtlı kervan rotalarının şehir kapılarına yaklaşmasını yeni rotalarla uyumlu hale getirir.

- `route_2.txt`, `route_10002.txt` ve `route_10013.txt` içindeki doğrulanmış kapı durma noktası, oyun tablosundaki kapı menzili içinde kaldığında kullanılır. Böylece botun eski rotadan ayrılıp geçilemeyen kapı merkezine yürümesi önlenir.
- Kayıtlı nokta kapı menzili dışındaysa oyun tablosundaki kapı merkezi kullanılmaya devam eder. Yeni çizilen rotalar ve kapı kimliklerinin doğrulanması korunur.
- Bot, Manager ve kurulum aracı aynı Windows yayın paketinde oluşturulur.

Otomatik testler geçti. Gerçek oyun sunucusunda eski ve yeni rotayla kapı geçişleri ayrıca doğrulanmalıdır.
