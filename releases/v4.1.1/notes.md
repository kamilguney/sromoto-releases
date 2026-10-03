# Sromoto 4.1.1

Bu yama sürümü, oto kervan sırasında şehir geçişinin eski harita bilgisi nedeniyle durmasını düzeltir.

- Sunucu ışınlanmayı kabul edip sahne hazır yanıtını verdikten sonra gelen eski şehrin harita listesi, hedef şehrin doğrulaması sayılmaz.
- Hedef şehrin harita bilgisi gecikirse bot bu bilgiyi yeniden sorgular ve gelen yanıtları dinler. Hedef harita doğrulanırsa kervan rotası sürer; doğrulanmazsa yanlış haritada rota yürütülmez.
- Eski harita yanıtının tekrar gelmesi ve hedef harita yanıtının gecikmesi için regresyon testleri eklendi.

Not: Canlı sunucudaki paket zamanlaması değişebilir. Güvenli üst bekleme süresinde hedef harita doğrulanmazsa bot rotayı durdurur.
