# Orbay Hukuk Bürosu Web Sitesi

Bu proje, Aksaray'da faaliyet gösteren kurucu avukat ve arabulucu İlker Orbay için hazırlanmış tek sayfalık bir tanıtım sitesidir. Statik HTML ve CSS ile oluşturulan sayfa; profesyonel profil, uzmanlık alanları, arabuluculuk yaklaşımı, yayınlar ve iletişim bölümlerini içerir.

## İçerik
- `index.html`: Sayfa iskeleti, bölümler, bağlantılar ve içerik metinleri.
- `styles/main.css`: Tipografi, renk paleti ve duyarlı tasarım kurallarını tanımlar.

## İletişim ve Hizmet Bilgileri
- Telefon: `0542 234 89 68`
- E-posta: `avukat@ilkerorbay.com`, `arabulucu@ilkerorbay.com`
- Adres: `Taşpazar Mah. 865. Sok. Alemdar Sitesi Kültürpark Evleri B-Blok Kat:1 No:1, 68100 Merkez/Aksaray`
- Hizmet alanları: Aile Hukuku, Ceza Hukuku, İş Hukuku, Ticaret Hukuku, Miras Hukuku, Tazminat Davaları, İcra ve İflas Hukuku, Sözleşmeler Hukuku, Arabuluculuk Hizmetleri

Form aracılığıyla gönderilen talepler `mailto:avukat@ilkerorbay.com` adresine yönlendirilir ve kullanıcının varsayılan e-posta istemcisinde yeni bir mesaj taslağı açar. İletişim bölümünde ayrıca Google Haritalar yerleştirmesi ve çalışma saatleri bileşeni bulunur.

## Renk Paleti
Site, old money yeşili ve koyu lacivert tonlarının dengeli bir harmanıyla güncellendi:

| Adı | Hex | Kullanım |
| --- | --- | --- |
| Koyu Lacivert | `#0A1B33` | Başlıklar, koyu arka plan geçişleri |
| Derin Lacivert | `#050D1F` | Alt bilgi, overlay ve gölgelendirme |
| Old Money Yeşili | `#1F3B2B` | Birincil butonlar, vurgu metinleri |
| Parlak Old Money Yeşili | `#2F5A41` | Logo, alıntı ve etiket vurguları |
| Fildişi | `#F5F6F2` | İçerik arka planı, yumuşak bölümler |
| Yumuşak Gri-Yeşil | `#DFE5DD` | Kenarlıklar ve form elemanları |

## Önerilen Geliştirmeler
- **Çok Dilli Destek:** Türkçe dışında İngilizce içerik hazırlayarak yabancı müvekkil adaylarına erişilebilirlik sağlayabilirsiniz.
- **Vaka Sonuçları & Referanslar:** Gizlilik sınırlarını aşmadan başarı hikâyeleri, müvekkil yorumları veya örnek vaka çözümleri eklemek güven duygusunu artırır.
- **Blog / Makale Alanı:** Arabuluculuk ve güncel hukuk değişikliklerine dair makaleler yayınlayarak uzmanlık görünürlüğünü yükseltebilirsiniz.
- **Randevu Planlama:** Google Calendar veya Calendly entegrasyonu ile danışanların doğrudan görüşme saati seçmesini kolaylaştırabilirsiniz.

## Geliştirme
1. Yerel ortamınızda bir HTTP sunucusu çalıştırın. Örnek: `python -m http.server` komutu ile 8000 portunda basit bir sunucu başlatabilirsiniz.
2. Tarayıcıdan `http://localhost:8000` adresine giderek sayfayı görüntüleyin.

## Foursquare'de Hukuk Bürosunu Aktifleştirme Adımları
1. [Foursquare for Business](https://business.foursquare.com/places/) hesabı oluşturun veya giriş yapın.
2. "Claim a Venue" adımında ofis adresinizi aratın. Sonuç yoksa "Add New Place" ile yeni bir kayıt açın.
3. İşletme adı olarak "Av. İlker Orbay Avukatlık & Arabuluculuk Bürosu" resmi unvanınızı, Aksaray'daki ofis adresinizi, `0542 234 89 68` telefon numaranızı, web sitesi bağlantınızı ve çalışma saatlerinizi eksiksiz girin.
4. Foursquare tarafından sunulan doğrulama yöntemlerinden (telefon, e-posta ya da posta ile PIN) size uygun olanı tamamlayın.
5. Doğrulama sonrası profilinizi ofis fotoğrafları, uzmanlık alanları ve arabuluculuk hizmetlerinize dair açıklamalarla zenginleştirin.
6. Web sitesi bağlantısı alanına bu projedeki sayfayı ekleyerek danışanların doğrudan iletişim kurmasını sağlayın.

### Siteyi Yayınlama ve Foursquare Profiline Bağlama
1. **Kaynak dosyaları yayımlayın:** `index.html` ve `styles/` klasörünü bir statik site barındırıcısına yükleyin. GitHub Pages, Netlify veya Vercel tek tıkla yayınlama için uygundur.
2. **Alan adınızı yönlendirin:**
   - Kendi alan adınızı kullanıyorsanız DNS kayıtlarınızı (A veya CNAME) seçtiğiniz barındırıcının yönlendirdiği IP/adrese güncelleyin.
   - Eğer hazır bir Foursquare kısa alan adınız varsa (ör. `foursquare.com/v/av-ilker-orbay...`), profilinizdeki **Website** alanına kendi alan adınızı ekleyin; Foursquare yönlendirmeyi otomatik yapar.
3. **HTTPS doğrulaması:** Barındırıcı panelinde ücretsiz SSL sertifikasını (Let’s Encrypt vb.) aktifleştirerek ziyaretçilerin güvenli bağlantıyla siteye erişmesini sağlayın.
4. **Foursquare profilini güncelleyin:** Foursquare Business panelinde “Website” alanına canlı sitenizin URL’sini (ör. `https://www.orbayhukuk.com`) girin ve kaydedin. Değişiklikler genelde birkaç dakika içinde yayınlanır.
5. **Takip edin:** Yayın sonrası Foursquare analitiklerinde tıklama sayısını izleyerek kampanyalarınızın performansını değerlendirebilirsiniz. Gerektiğinde profil açıklamasına WhatsApp bağlantısı veya randevu formu URL’si ekleyin.

Ek olarak, arabuluculuk hizmetlerinizi vurgulamak için Foursquare profilinizde randevu bağlantısı paylaşabilir, gelen yorumları düzenli olarak yanıtlayarak dijital görünürlüğünüzü güçlendirebilirsiniz.
