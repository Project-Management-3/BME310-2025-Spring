Randevu Alma Ekranı Wireframe
Ekran Adı: Randevu Al
Açıklama: Kullanıcının hastane, bölüm, doktor ve tarih-saat seçerek randevu oluşturduğu ekran. Mobil uyumlu, sade ve kullanıcı dostu bir düzen hedeflenmiştir.
Amaç

Kullanıcıların kolayca randevu oluşturmasını sağlamak.
Hastane, bölüm ve doktor seçimini sezgisel hale getirmek.
Tarih ve saat seçimini hızlı ve hatasız yapmak.
Kullanıcıyı yönlendiren net bir akış sunmak.

Bileşenler

Header:
Geri Butonu: Sol üst, önceki ekrana (ör. Ana Ekran) döner.
Başlık: Ortalanmış, "Randevu Al" metni.


Form Alanı:
Hastane Seçimi: Dropdown menü, Acıbadem hastaneleri listelenir (ör. Acıbadem Maslak, Acıbadem Kadıköy).
Bölüm Seçimi: Dropdown menü, tıbbi bölümler listelenir (ör. Kardiyoloji, Ortopedi).
Doktor Seçimi: Dropdown veya liste, seçilen hastane ve bölüme göre filtrelenmiş doktorlar.
Tarih ve Saat Seçimi: Takvim (tarih için), saat dilimleri (ör. 09:00, 10:00) için seçim alanı.


Onay Butonu:
"Randevuyu Kaydet" butonu, formu gönderir ve randevuyu onaylar.



Görsel Düzen
[Header: Geri (sol) | Randevu Al (ortada)]
[Form: 
  [Hastane: Dropdown]
  [Bölüm: Dropdown]
  [Doktor: Dropdown/Liste]
  [Tarih-Saat: Takvim + Saat Seçici]
]
[Onay: Randevuyu Kaydet Butonu]

Kullanıcı Akışı

Giriş: Kullanıcı, Ana Ekran’daki “Randevu Al” butonuna tıklayarak bu ekrana gelir.
Seçimler:
Kullanıcı önce hastaneyi seçer (dropdown açılır, listeden seçim yapılır).
Bölüm seçilir (hastane seçimine göre filtrelenmiş).
Doktor seçilir (hastane ve bölüme göre filtrelenmiş).
Tarih ve saat seçilir (takvim ve saat dilimleri gösterilir).


Onay: Kullanıcı “Randevuyu Kaydet” butonuna tıklar, sistem randevuyu kaydeder ve onay ekranına yönlendirir.
Geri Dönüş: Geri butonu, kullanıcıyı Ana Ekran’a döndürür.

Tasarım Notları

Mobil Uyumluluk: Ekran, küçük ekranlarda (ör. 320px genişlik) düzgün görünmeli. Dropdown’lar ve butonlar sıkışmamalı.
Erişilebilirlik: Dropdown’lar ve seçim alanları, ekran okuyucularla uyumlu olmalı (ör. ARIA etiketleri).
Performans: Dropdown verileri (hastane, bölüm, doktor) API’den hızlıca yüklenebilir.
Esneklik: Form, gelecekte ek alanlar (ör. randevu türü: fiziksel/video) için genişletilebilir.
Hata Önleme: Onay butonu, tüm alanlar doldurulmadan aktif olmamalı.

Varsayımlar

Kullanıcı oturum açmış durumdadır.
Hastane, bölüm ve doktor listeleri dinamik olarak API’den çekilir.
Tarih-saat seçimi, doktorun uygunluk durumuna göre filtrelenir.
Onay sonrası bir onay ekranı veya bildirim gösterilir.
