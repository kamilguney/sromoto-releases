# Sromoto 6.2.0

## Ekipman ve envanter
- Çanta ve kuşanılmış eşyalarda ekipman puanı, eşya türü ve ayrıntılı nitelikler gösterilir.
- Temel nitelikler, eşyaya özel güçlendirmeleriyle birlikte gösterilir; Güç ve Zekâ gibi Blue nitelikler ayrı listelenir.
- Uygun seviyedeki, karakterin kullandığı ekipman türüyle uyumlu ve puanı daha yüksek ganimetler otomatik kuşanılır. Bilinmeyen puanlarda veya doğrulanmamış envanterde otomatik değişim yapılmaz.
- Kombo silahı eşleştirmelerinde tekrarlanan doğrulama ve aynı yuva için biriken değişim istekleri giderildi.

## Yol bulma ve otomasyon
- Navmesh yolları, yürünebilir üçgen koridorunda raycast kontrolleriyle sadeleştirilir; gereksiz ara hedefler azaltılır.
- Yol bulunamaması, geçici koruma verisi eksikliği ve aynı karakterin yeniden bağlanması için bekleme ve toparlanma akışları iyileştirildi.
- Aktif kervan süresinde kaybedilen boş bineğin yeniden hazırlanması ve kanal/meslek geçişlerinin beklenmesi iyileştirildi.
- Manager durum alanında seyahat, bekleme ve hata nedenleri daha açık gösterilir.

## Performans ve kararlılık
- Yerelleştirme verileri aynı süreçte paylaşılır; yinelenen yükleme ve eşya kurallarındaki gereksiz bellek ayırmaları azaltıldı.
- Buff durumları okunurken oluşabilen eşzamanlı liste değişimi hatası giderildi.

Oyun uyumluluğu: **2.0.9.5.134-e3da5cd**. Güncellemeden önce çalışan botları kapatın; mevcut hesap ve tercih dosyaları korunur.
