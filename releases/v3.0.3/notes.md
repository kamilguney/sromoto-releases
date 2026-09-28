# Sromoto 3.0.3

Bu sürüm masaüstü kullanımını ve güncelleme bildirimlerini iyileştirir. Binek hızı düzeltmesi canlı oyun oturumunda ayrıca doğrulanmalıdır.

## İyileştirmeler

- Yeni Sromoto simgesi pencere, sistem tepsisi ve Windows çalıştırılabilir dosyasında kullanılır.
- Pencerenin X düğmesi botu durdurmadan sistem tepsisine gizler. Tepsi simgesine sağ tıklayıp **Botu Kapat** seçilerek uygulama kapatılır.
- Güncelleme bildirimi sağ üstteki zil simgesine taşındı. Yeni sürüm geldiğinde zil renk değiştirir; son sürümün notları buradan okunabilir.
- İmzalı güncelleme paketi oyun açıkken arka planda indirilebilir; kurulum kullanıcı onayı ve kapalı oyun oturumu gerektirir. Yeni sürümler uygulama açıkken düzenli aralıklarla kontrol edilir.
- CPU ve RAM kullanımı uygulamanın alt kısmında gösterilir.

## Hata düzeltmeleri

- Kervan hazırlığı ve şehir geçişlerinde sunucunun 2–4 aşamalarında bildirdiği canlı binek artık hız izlemesinden çıkarılmaz. Bineğin kendi UID'sine ait sunucu hareket hızı, tam özellik bildirimi henüz gelmese de kullanılabilir.
- Sunucu hareket paketindeki anlık sıfır hız, duran bineğin kalıcı hız kapasitesi sıfırmış gibi gösterilmez.

Not: Canlı oyun sunucusunda şehirler arası hız doğrulaması yapılmadı; doğrulanmamış tablo değeri binek hızı olarak gösterilmez.
