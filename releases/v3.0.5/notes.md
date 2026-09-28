# Sromoto 3.0.5

Bu sürüm yeni hesaplarla giriş akışını ve giriş hatalarının teşhisini iyileştirir.

## Düzeltmeler

- `GetProfile` tarafından döndürülen doğrulanmış kullanıcı adı oyun kimlik doğrulamasında ve karakter listesi sorgusunda kullanılır. Yeni hesapla oyuna giriş canlı olarak doğrulandı; önceden kayıtlı hesapla giriş de doğrulandı.
- Kayıtlı bir hesaptan farklı kullanıcı adına geçildiğinde önceki hesabın karakter seçimi ve kayıtlı parolası yeni girişe taşınmaz.
- Oyun kimlik sunucusu gateway bileti vermezse boş biletle devam edilmez; yalnız paket boyutu, alan numaraları ve sayısal hata kodları loglanır. Ham kimlik paketleri ve tokenlar terminale yazdırılmaz.
- Gateway giriş reddi sayısal koduyla gösterilir. Yinelenen `GetProfile` tanımı kaldırıldı ve profil hatalarında hassas yanıt metni loglanmaz.

Not: Gamo `Login` bazen `202` kodu döndürdü; bu yanıt Auth aşamasından önce gelir. Bu sunucu yanıtının nedeni henüz doğrulanmadı ve sürüm onu çözdüğünü iddia etmez.
