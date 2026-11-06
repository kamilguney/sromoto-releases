# Sromoto 6.0.2 — Otomasyon ve Aktarım Kararlılığı

Oyun sürümü: `2.0.7.5.127-ec5802a`.

- Kanalın sahne onayı gecikirse otomasyon kapanmaz; işlem kilidini bırakarak bekler ve yeni işlemden önce sunucunun güncel kanalını yeniden sorgular. Durdur bu beklemeyi iptal eder.
- Eğitim başlangıcında kendi sunucu konumu beklenir. Buff için HP verisi eksikse veya karakter hayatta değilse buff gönderilmez; güncel veri geldiğinde devam edilir.
- Kendi karakterine uygulanabildiği doğrulanmayan buff, adıyla uyarı verilerek atlanır; geçerli saldırılar ve diğer doğrulanmış bufflar kullanılmaya devam eder.
- Oto Kervan ekranındaki rota, ürün, adet, yıldız ve tekrar seçimi çalışan kervandan güncellenir. Otomasyonun başlattığı sefer yerine eski elle seçim gösterilmez.
- Sıradan kervan durum sorguları, gerçek başlangıç hatasını veya devam eden hazırlık adımını artık gizlemez. Aktif kayıt/mal bulunmaması tek başına bir başlangıç hatası değildir; yeni kayıt için mevcut hak ve hazırlık kontrolleri korunur.
- Çanta sıralama işareti ve geri dönüş eşya bildirimleri aktarım verisini gereksiz yere geçersiz saymaz. Daha önce tüketildiği/silindiği doğrulanan yığınların tekrar sıfırlanması/silinmesi güvenli biçimde işlenir. Bilinmeyen pozitif stok, çakışan konum ve belirsiz RPC sonuçları doğrulanmış sayılmaz.
- Farm için ulaşım başarısız olursa diğer haritalardaki uygun bölgeler değerlendirilir; mevcut oyun ışınlanma/kapı ve navmesh yolları kullanılır. İşaretin çevresindeki yürünebilir alan farm yarıçapına göre aranır. Uygun hedef geçici olarak bulunamazsa koşullar yeniden kontrol edilir, Dünya rezervi boşa açılmaz.
- Navmesh ara hedefleri hareket göndericisine birlikte aktarılır; onaylanan ara noktada sonraki ekran kontrolünü beklemeden bir sonraki hedefe geçilir. Sunucunun hız ve olumsuz etki verileri korunur.

6.0.1'deki Windows sertifika deposu düzeltmesi bu sürümde bulunur. Eski kurulum aracı SSL hatası veriyorsa yeni SromotoSetup.exe dosyasını tarayıcıyla indirin ve mevcut Sromoto klasörünü seçin. Düzeltmeler otomatik testlerle doğrulanmıştır; her hesap ve uzun süreli canlı kullanım sonucu ayrıca gözlenmelidir.
