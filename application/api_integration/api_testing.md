Tüm API Bağlantılarının Test Edilmesi (Backend + Frontend)
Amaç:
Backend ve frontend arasındaki tüm veri akışının doğru ve güvenli çalıştığını garanti altına almak.

Yapılan Çalışmalar:
Frontend tarafında her API çağrısı Axios ile gerçekleştirildi ve sonuçlar kontrol edildi.

Postman kullanılarak manuel API endpoint testleri yapıldı.

Başarısız API yanıtları için kullanıcı dostu hata mesajları geliştirildi.

Token expiration durumunda otomatik yeniden kimlik doğrulama mekanizması geliştirildi.

Kullanılan Teknolojiler:
Postman

Axios

Jest (bazı unit testler için)

React Testing Library

Karşılaşılan Zorluklar:
API cevap sürelerini optimize etmek amacıyla frontend request optimizasyonu yapıldı.

Gelecek Adımlar:
Otomatik API testlerini CI/CD süreçlerine entegre etmek.
