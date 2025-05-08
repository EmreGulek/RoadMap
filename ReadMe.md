Seyahat Uygulaması - RoadMap Projesi

Bu proje, kullanıcıların seyahat planları yaparken harita ve hava durumu bilgilerini entegre bir şekilde kullanabilmesini sağlayan bir seyahat uygulamasıdır. Uygulama, harita verisi ve hava durumu bilgilerini sağlamak için API'leri kullanmaktadır. Proje, React.js, .NET ve NoSQL veritabanı teknolojilerini içermektedir.
Teknolojiler

Frontend: React.js
Backend: .NET
Veritabanı: NoSQL (MongoDB veya başka bir NoSQL veritabanı)
Harita API'si: Google Maps API veya OpenStreetMap API
Hava Durumu API'si: OpenWeatherMap API
Proje Özeti

Seyahat Uygulaması, kullanıcıların seyahat etmek istedikleri lokasyonları harita üzerinde görselleştirmelerine ve seçtikleri bölgenin hava durumu bilgilerini öğrenmelerine olanak tanır. Uygulama ayrıca, kullanıcıların geçmiş seyahat verilerini kaydederek, onları kişisel seyahat geçmişleriyle ilişkilendirmelerine olanak sağlar.
Kurulum

Gereksinimler
Node.js ve npm
.NET SDK
MongoDB veya NoSQL veritabanı (alternatif olarak, MongoDB Atlas kullanılabilir)
Frontend Kurulumu
Proje dosyasını klonlayın:
git clone https://github.com/kullanici/seyahat-uygulamasi.git
cd seyahat-uygulamasi
Gerekli paketleri yükleyin:
npm install
Uygulamayı başlatın:
npm start
Tarayıcınızda http://localhost:3000 adresine giderek uygulamayı görüntüleyebilirsiniz.
Backend Kurulumu
Proje dosyasını klonlayın (Backend için):
git clone https://github.com/kullanici/seyahat-uygulamasi-backend.git
cd seyahat-uygulamasi-backend
Gerekli bağımlılıkları yükleyin:
dotnet restore
Uygulamayı başlatın:
dotnet run
Backend sunucusu, http://localhost:5000 adresinde çalışacaktır.
NoSQL Veritabanı Kurulumu
MongoDB'yi yükleyin ve başlatın (ya da MongoDB Atlas kullanarak bir bulut veritabanı oluşturun).
Veritabanı bağlantı bilgilerini .NET projenizin yapılandırma dosyasına ekleyin.
Kullanım

Harita: Seyahat etmek istediğiniz lokasyonu harita üzerinde arayın ve detayları görüntüleyin.
Hava Durumu: Seçtiğiniz lokasyonun hava durumu bilgisini anlık olarak sorgulayın.
Geçmiş Seyahatler: Geçmişteki seyahatlerinizi inceleyebilir ve kaydedebilirsiniz.
API Entegrasyonları

Harita API'si
Google Maps veya OpenStreetMap API'si, kullanıcıların harita üzerinde etkileşimli bir deneyim yaşamasını sağlar. Uygulama, bu API üzerinden harita verilerini çekmekte ve kullanıcılar için yön tarifi sunmaktadır.
Hava Durumu API'si
OpenWeatherMap API'si, kullanıcıların lokasyonlarına dair güncel hava durumu bilgilerini sağlar. Uygulama, bu API'yi kullanarak hava durumu tahminlerini göstermektedir.
