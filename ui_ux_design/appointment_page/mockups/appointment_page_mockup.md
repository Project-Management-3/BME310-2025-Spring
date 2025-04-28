Randevu Alma Ekranı Mockup
Ekran Adı: Randevu Al
Açıklama: Acıbadem Online uygulamasının Randevu Alma Ekranı için görsel tasarım. Kullanıcıların hastane, bölüm, doktor ve tarih-saat seçerek randevu oluşturmasını sağlayan, mobil uyumlu bir arayüz. Renk paleti, tipografi ve stil, Acıbadem’in kurumsal kimliğiyle uyumludur ve Ana Ekran tasarımıyla tutarlıdır.
Amaç

Kullanıcıların randevu oluşturma sürecini görsel olarak net ve kolay hale getirmek.
Form elemanlarını sezgisel ve estetik bir şekilde sunmak.
Mobil cihazlarda sorunsuz bir deneyim sağlamak.
Kurumsal renkler ve stil ile profesyonel bir görünüm oluşturmak.

Tasarım Detayları
Renk Paleti

Ana Renk: Mavi (#005670) - Header, onay butonu ve vurgular için.
Arka Plan: Beyaz (#FFFFFF) - Temiz ve ferah bir görünüm.
Vurgu Rengi: Turuncu (#F5A623) - Geri butonu ve aktif seçimler için.
Kenarlık/Metn: Açık Gri (#F5F5F5) - Dropdown kenarları, pasif elemanlar.
Metin: Koyu Gri (#333333) - Okunabilirlik için.

Tipografi

Font: Roboto (modern, okunabilir, Google Fonts’tan).
Boyutlar:
Başlık (header): 24px, kalın.
Form etiketleri: 16px, normal.
Dropdown/saat seçenekleri: 14px, normal.
Buton: 16px, kalın.


Hizalamalar: Sola hizalı (form etiketleri), ortalanmış (başlık, buton).

Görsel Öğeler

Geri Butonu: Turuncu ok ikonu, 24px.
Dropdown’lar: Beyaz zemin, gri kenarlık (1px), yuvarlak köşeler (8px).
Takvim/Saat Seçici: Beyaz zemin, gri kenarlık, takvim için küçük bir ikon.
Onay Butonu: Mavi, yuvarlak köşeli, beyaz yazı.

Bileşenler

Header:
Arka plan: Mavi (#005670).
Geri Butonu: Sol üst, turuncu (#F5A623) ok ikonu (←).
Başlık: Ortalanmış, “Randevu Al”, beyaz, 24px, kalın.


Form Alanı:
Hastane Seçimi:
Dropdown, beyaz zemin, gri kenarlık (#F5F5F5, 1px).
Placeholder: “Hastane Seçin”.
Örnek seçenekler: Acıbadem Maslak, Acıbadem Kadıköy.


Bölüm Seçimi:
Dropdown, aynı stil.
Placeholder: “Bölüm Seçin”.
Örnek seçenekler: Kardiyoloji, Ortopedi, Dermatoloji.


Doktor Seçimi:
Dropdown, aynı stil.
Placeholder: “Doktor Seçin”.
Örnek seçenekler: Dr. Ahmet Yılmaz, Dr. Ayşe Demir.


Tarih ve Saat Seçimi:
Takvim: Beyaz zemin, gri kenarlık, küçük takvim ikonu.
Saat: Dropdown veya butonlar (ör. 09:00, 10:00), aynı stil.




Onay Butonu:
Metin: “Randevuyu Kaydet”.
Stil: Mavi (#005670), beyaz yazı, yuvarlak köşeler (8px), 12px padding.
Konum: Formun altında, ortalanmış.



Görsel Düzen
[Header: Mavi | Turuncu Geri (←) | Randevu Al (beyaz)]
[Form: 
  [Hastane: Beyaz Dropdown, gri kenar]
  [Bölüm: Beyaz Dropdown, gri kenar]
  [Doktor: Beyaz Dropdown, gri kenar]
  [Tarih-Saat: Takvim + Saat Dropdown]
]
[Onay: Mavi Buton, beyaz yazı]

Kullanıcı Deneyimi (UX) Notları

Erişim Kolaylığı: Dropdown’lar ve butonlar büyük (min. 48x48px), mobil parmak dostu.
Görsel Hiyerarşi: Başlık ve onay butonu öne çıkar, form elemanları düzenli.
Animasyonlar (opsiyonel): Dropdown açıldığında hafif bir geçiş, butona hover’da renk koyulaşması (#004050).
Erişilebilirlik: Form elemanlarında ARIA etiketleri, yüksek kontrast (mavi/beyaz).

Tasarım Notları

Mobil Uyumluluk: Ekran, 320px-768px genişliklerde düzgün görünür. Dropdown’lar ve butonlar sıkışmaz.
Kurumsal Kimlik: Mavi ve turuncu, Acıbadem’in marka renkleriyle uyumlu.
Esneklik: Form, ek alanlar (ör. randevu türü) için genişletilebilir.
Hata Önleme: Onay butonu, tüm alanlar doldurulmadan gri (#CCCCCC) ve pasif olur.

Varsayımlar

Form verileri (hastane, bölüm, doktor) API’den dinamik olarak çekilir.
Tarih-saat seçimi, doktorun uygunluğuna göre filtrelenir.
Geri butonu, Ana Ekran’a döner.
Onay sonrası bir onay ekranı veya bildirim gösterilir.
