Backend Sunucusu ve Veritabanı Yapısının Kurulması
Amaç:
Uygulamanın temel işlevlerinin çalışabilmesi için güvenli, hızlı ve sürdürülebilir bir backend altyapısı oluşturmak. Verilerin doğru şekilde depolanması ve yönetilmesi için uygun veritabanı sisteminin kurulması.

Yapılan Çalışmalar:
Node.js tabanlı bir Express.js sunucu uygulaması geliştirildi.

Sunucunun temel yapılandırmaları (port ayarları, middleware yönetimi) yapıldı.

PostgreSQL veritabanı kuruldu ve erişim yapılandırıldı.

Sequelize ORM kullanılarak veritabanı ile sunucu arasında güvenli bir bağlantı sağlandı.

Kullanıcı, randevu ve reçete verileri için ilişkili tablolar tasarlanarak veri modellemesi yapıldı.

Sunucu güvenliği için CORS politikaları düzenlendi, input validation ve basic error handling sistemleri geliştirildi.

Kullanılan Teknolojiler:
Node.js

Express.js

PostgreSQL

Sequelize ORM

dotenv (çevre değişkenleri yönetimi için)

Helmet.js (HTTP güvenlik başlıkları için)

Karşılaşılan Zorluklar:
Veritabanı bağlantısında SSL gerekliliği için ek yapılandırmalar yapılması gerekti.

API performansını optimize etmek için veritabanı sorguları iyileştirildi.

Gelecek Adımlar:
Database için günlük otomatik yedekleme sistemi kurulacak.

Sunucu tarafında kapsamlı hata yönetimi (error-logging middleware) geliştirilecek.
