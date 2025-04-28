API'lere Bağlantı Sağlanması (Randevular, Video Görüşme, Reçeteler)
Amaç:
Frontend ve backend arasındaki veri akışını sağlamak için RESTful API uç noktalarının tasarlanması ve hayata geçirilmesi. Kullanıcıların uygulama üzerinde randevu oluşturabilmesi, video görüşme başlatabilmesi ve reçetelerine ulaşabilmesi sağlanacak.

Yapılan Çalışmalar:
/appointments endpoint'i ile yeni randevu oluşturma, listeleme ve iptal işlemleri sağlandı.

/video-calls endpoint'i ile video görüşme oturumu oluşturma ve yönetme akışı kuruldu.

/prescriptions endpoint'i üzerinden reçete bilgilerine erişim ve güncelleme imkanı sağlandı.

Her API için JWT authentication ile güvenli veri transferi sağlandı.

Swagger kullanılarak API dokümantasyonu oluşturuldu.

Kullanılan Teknolojiler:
Express.js Router

JWT Authentication

Swagger UI

Bcrypt.js (şifre güvenliği için)

Karşılaşılan Zorluklar:
Video görüşme oturumu için token bazlı zaman aşımı yönetimi geliştirildi.

API endpoint performansı artırıldı; sadece yetkili kullanıcıların ilgili verilere ulaşması sağlandı.

Gelecek Adımlar:
API'lere rate-limiting ve IP-blocking mekanizmalarının entegre edilmesi planlanıyor.
