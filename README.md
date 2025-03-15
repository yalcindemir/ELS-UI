# ELS - Elektronik Etiket Sistemi

## Proje Genel Bakış

ELS (Elektronik Etiket Sistemi), LoRaWAN ağı üzerinden veri alışverişi yapabilen, pil veya şarjlı pil ile çalışan elektronik etiket sistemidir. Bu proje, elektronik etiketlerin modern ve verimli bir şekilde yönetilmesini sağlayan web arayüzü ve API erişim tanımlamalarını içermektedir.

## Teknoloji Altyapısı

- **Frontend**: React.js
- **Backend**: Java Spring Boot (Mikroservis mimarisi)
- **Veritabanı**: (Kullanılacak veritabanı burada belirtilecektir)
- **İletişim**: LoRaWAN protokolü

## Amaç ve Hedefler

- LoRaWAN ağı üzerinden veri alışverişi sağlayan elektronik etiket sisteminin geliştirilmesi
- Pil veya şarjlı pil ile çalışan uzun ömürlü cihazların tasarlanması
- Web arayüzü ve API üzerinden etiket ekranlarının güncellenebilmesi
- Mobil cihazlar (telefon, tablet) üzerinden etiket yönetimi
- Stok sayımı ve ek modüller (sıcaklık, nem, GPS) desteği
- Fatura ödeme ve abonelik takip sistemi
- Cihaz yönetimi ve yetkilendirme sistemi
- Mağaza/depo tanımlama ve yönetimi

## Sistem Özellikleri

### Donanım Özellikleri

- LoRaWAN ağı üzerinden iletişim
- Pil veya şarjlı pil ile uzun süreli çalışma
- Ek modül desteği:
  - Sıcaklık sensörü
  - Nem sensörü
  - GPS modülü
- Stok sayımı için optimize edilmiş tasarım

### Yazılım Özellikleri

#### Web Arayüzü

- Kullanıcı dostu dashboard
- Etiket içerik yönetimi
- Gerçek zamanlı etiket durumu izleme
- Detaylı raporlama ve analiz araçları
- Responsive tasarım (masaüstü, tablet ve mobil uyumlu)

#### API Erişimi

- RESTful API desteği
- Güvenli kimlik doğrulama
- Etiket içerik güncelleme
- Cihaz durumu sorgulama
- Batch işlem desteği

#### Mobil Uygulama

- iOS ve Android desteği
- Etiket yönetimi
- QR kod tarama
- Anlık bildirimler
- Offline çalışma modu

### Yönetim Özellikleri

- Kullanıcı ve yetki yönetimi
  - Rol tabanlı erişim kontrolü
  - Çoklu kullanıcı desteği
  - Detaylı yetkilendirme seçenekleri
  
- Cihaz yönetimi
  - Cihaz ekleme/çıkarma
  - Cihaz gruplandırma
  - Toplu güncelleme
  - Cihaz durumu izleme
  
- Mağaza/Depo yönetimi
  - Mağaza/depo tanımlama
  - Lokasyon bazlı cihaz gruplandırma
  - Mağaza/depo bazlı raporlama
  
- Fatura ve abonelik yönetimi
  - Abonelik planları
  - Otomatik fatura oluşturma
  - Ödeme takibi
  - Abonelik yenileme ve iptal işlemleri

## Teknik Gereksinimler

- Web tarayıcı (Chrome, Firefox, Safari, Edge)
- Mobil cihazlar için iOS 12+ veya Android 8+
- LoRaWAN ağ erişimi
- API entegrasyonu için internet bağlantısı
- Node.js ve npm (Frontend geliştirme için)
- Java JDK 11+ ve Maven/Gradle (Backend geliştirme için)
- Git

## Kurulum ve Yapılandırma

### Gereksinimler

- Git
- Node.js (v14.x veya üzeri)
- npm (v6.x veya üzeri)
- Java JDK 11+
- Maven veya Gradle

### Frontend (React.js) Kurulumu

```bash
# Projeyi klonlayın
git clone https://github.com/kullanici/ELS-UI.git
cd ELS-UI

# Bağımlılıkları yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm start

# Üretim için build alın
npm run build
```

### Backend (Spring Boot) Kurulumu

```bash
# Backend projesini klonlayın
git clone https://github.com/kullanici/ELS-Backend.git
cd ELS-Backend

# Maven ile build alın
./mvnw clean install

# Uygulamayı başlatın
./mvnw spring-boot:run

# Alternatif olarak Gradle ile build alın
./gradlew build

# Uygulamayı başlatın
./gradlew bootRun
```

### Ortam Değişkenleri

Frontend ve backend için gerekli ortam değişkenleri `.env` veya `application.properties/yml` dosyalarında yapılandırılmalıdır. Örnek yapılandırma dosyaları projelerde mevcuttur.

## API Dokümantasyonu

API dokümantasyonu Swagger UI aracılığıyla erişilebilir olacaktır. Uygulama çalıştırıldıktan sonra aşağıdaki URL üzerinden erişilebilir:

```
http://localhost:8080/swagger-ui.html
```

## Sürüm Geçmişi

- v1.0.0 - İlk sürüm

## İletişim ve Destek

(İletişim ve destek bilgileri burada yer alacaktır)