İLİM — Kişisel ilim, öğrenme ve araştırma platformu
Sürüm: 1.3.0 (kapsamlı geliştirme adayı)

DOSYALAR
- index.html: uygulama arayüzü, içerikler ve yerel işlevler
- manifest.webmanifest: PWA tanımı
- sw.js: çevrimdışı önbellek
- icon.svg: uygulama simgesi

ANA YAPI
- 9 ana bilgi alanı
- Kaynaklı makaleler ve ileri seviye incelemeler
- Âlimler, ilmî eserler, şerh-hâşiye ilişkileri ve terimler sözlüğü
- Seviyeli müfredat: başlangıç, orta, ileri, ihtisas
- Klasik eser merkezli okuma sıraları
- Bilgi kartları ve günlük genel kültür soruları
- Araştırma dosyaları, görüş karşılaştırma ve kaynak kayıtları
- Açık akademik kataloglara yönlendiren canlı arama bağlantıları
- Kavram bağlantıları ve merak zinciri
- Tarih kronolojisi, tarihî coğrafya harita bağlantıları ve âlimler arası fikrî ilişki ağı
- Kitap/PDF arşivi, favoriler, gelişim kaydı
- Dört tema, karanlık mod, yazı boyutu ve JSON yedekleme
- Kaldırılanlar: konu testi sistemi, aralıklı tekrar, münazara laboratuvarı, ayrı kişisel notlar ve günlük hedefler

KULLANIM
1. ZIP dosyasını çıkar.
2. index.html dosyasını tarayıcıda açarak temel arayüzü inceleyebilirsin.
3. PWA ve çevrimdışı önbellek için dosyaları bir HTTPS statik sunucuda (ör. GitHub Pages) yayımla.
4. Android Chrome'da siteyi açıp menüden Ana ekrana ekle/Uygulamayı yükle seçeneğini kullan.

GITHUB PAGES
1. Dosyaları GitHub deposunun ana dizinine yükle.
2. Settings > Pages bölümünde Deploy from a branch seç.
3. Branch: main, Folder: / (root) seçip kaydet.

VERİ VE GİZLİLİK
- Araştırmalar, kitaplar, favoriler, müfredat ilerlemesi, ayarlar ve PDF'ler cihazın yerel depolamasında tutulur.
- Hesap, bulut, sunucu ve cihazlar arası senkronizasyon yoktur.
- Tarayıcı verileri silinirse yerel kayıtlar kaybolabilir. Düzenli JSON yedeği al.
- PDF başına 5 MB sınırı vardır; tarayıcı depolama sınırları cihaza göre değişir.

İÇERİK VE KAYNAK İLKESİ
- İslâmî ilimlerde klasik ana metinler, şerhler ve hâşiyeler esas alınır.
- İhtilaflı konularda mezhep ve ekol farklılıkları ayrıştırılır.
- Eserlerin baskı ve sayfa bilgileri kullanılan nüshadan kontrol edilmelidir.
- Kaynak gösterimi tek başına iddianın doğruluğunu garanti etmez. Telifli eserler izinsiz çoğaltılmamalıdır.

ÖZELLİKLERİN SINIRLARI
- Akademik arama düğmeleri Google Scholar, OpenAlex, Crossref, DergiPark ve Internet Archive sorgularını açar. Sonuçları kullanıcı kontrol eder; otomatik kaynak doğrulaması değildir.
- Arapça yardımcı yerel sözlük eşleştirmesi yapar; otomatik sarf-nahiv tahlili veya yapay zekâ değildir.
- Metin inceleme aracı kelime ve cümle taraması yapar; yapay zekâ yorumu veya tahkik değildir.
- Ücretli API, zorunlu hesap veya sunucu yoktur. Gerçek bir yapay zekâ okuma asistanı bu sürümde etkin değildir.
- Çekirdek ekranlar çevrimdışı kullanılabilir; canlı arama ve dış bağlantılar internet ister.
- Günlük genel kültür soruları kısa bir bilgi etkinliğidir; konu testi ve sınav istatistiği sistemi bulunmaz.
