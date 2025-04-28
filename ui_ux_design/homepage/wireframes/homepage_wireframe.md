Ana Ekran Wireframe
Ekran Adı: Ana Ekran
Açıklama: Acıbadem Online uygulamasında kullanıcının giriş yaptıktan sonra gördüğü ilk ekran. Kullanıcıya temel işlevlere hızlı erişim, arama imkanı ve bildirimler sunar. Mobil uyumlu, sade ve kullanıcı dostu bir düzen hedeflenmiştir.
Amaç

Kullanıcıların temel özelliklere (randevu alma, video görüşme, reçete yönetimi) hızlıca ulaşmasını sağlamak.
Arama ve filtreleme ile doktor veya hastane bulmayı kolaylaştırmak.
Bildirimler ve kampanyalar aracılığıyla kullanıcıyı bilgilendirmek.
Alt menü ile uygulamada gezinmeyi basitleştirmek.

Bileşenler

Header:
Logo: Acıbadem Online logosu (sol üst).
Profil İkonu: Kullanıcı profil sayfasına yönlendiren ikon (sağ üst).


Arama Çubuğu:
Metin giriş alanı, placeholder: "Doktor, hastane veya hizmet ara...".
Arama simgesi (isteğe bağlı, sağda büyüteç ikonu).


Banner Alanı:
Tam genişlikte bir görsel veya metin.
Örnek içerik: Kampanya duyurusu ("Hemen Randevu Al!") veya bildirim ("Yeni tahlil sonuçlarınız hazır!").


Hızlı Erişim Butonları:
Randevu Al: Randevu ekranına yönlendirir.
Video Görüşme: Video konsültasyon ekranına yönlendirir.
Reçeteler: Reçete yönetimi ekranına yönlendirir.
Butonlar, yatay veya ızgara düzeninde (mobil uyumlu).


Alt Menü:
Sekmeler: Ana Sayfa, Randevular, Reçeteler, Profil.
Her sekme, bir ikon ve etiket içerir.
Sabit bir alt çubuk olarak ekranın altında yer alır.



Görsel Düzen
[Header: Logo (sol) | Profil İkonu (sağ)]
[Arama Çubuğu: Metin Giriş Alanı]
[Banner: Görsel/Duyuru Metni]
[Hızlı Erişim: [Randevu Al] [Video Görüşme] [Reçeteler]]
[Alt Menü: [Ana Sayfa] [Randevular] [Reçeteler] [Profil]]

Kullanıcı Akışı

Giriş: Kullanıcı, oturum açtıktan sonra Ana Ekran’a yönlendirilir.
Arama: Arama çubuğuna metin girerek doktor, hastane veya hizmet arar; sonuçlar ayrı bir ekranda gösterilir.
Hızlı Erişim:
"Randevu Al" butonu, randevu oluşturma ekranına gider.
"Video Görüşme" butonu, konsültasyon ekranına gider.
"Reçeteler" butonu, reçete listeleme ekranına gider.


Banner: Tıklanabilir ise ilgili kampanya veya bildirim detayına yönlendirir.
Alt Menü: Sekmeler, ilgili ekranlara (Ana Sayfa, Randevular, Reçeteler, Profil) geçiş yapar.
Profil İkonu: Profil düzenleme ekranına yönlendirir.

Tasarım Notları

Mobil Uyumluluk: Ekran, küçük ekranlarda (ör. 320px genişlik) düzgün görünmeli. Butonlar ve menüler sıkışmamalı.
Erişilebilirlik: Arama çubuğu ve butonlar, ekran okuyucularla uyumlu olmalı (ör. uygun ARIA etiketleri).
Performans: Banner görseli optimize edilmeli (ör. düşük boyutlu JPG/PNG).
Esneklik: Hızlı erişim butonları, gelecekte yeni özellikler (ör. Tahlil Sonuçları) için genişletilebilir.

Varsayımlar

Kullanıcı zaten oturum açmış durumdadır.
Banner içeriği, dinamik olarak güncellenebilir (ör. API ile).
Alt menü, tüm ekranlarda sabit kalır.
