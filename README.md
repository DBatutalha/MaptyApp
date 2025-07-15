# Mapty - Egzersiz Takip Uygulaması

![Mapty Logo](final/logo.png)

## Proje Hakkında

Mapty, kullanıcıların koşu ve bisiklet egzersizlerini interaktif bir harita üzerinde takip edebileceği, tamamen Vanilla JavaScript ile geliştirilmiş bir web uygulamasıdır. Uygulama, kullanıcının konumunu alır ve harita üzerinde egzersiz yapılan yerleri işaretleyerek detaylı istatistikler sunar.

## 🚀 Özellikler

### Ana İşlevler

- **Interaktif Harita**: Leaflet.js kullanılarak gerçek zamanlı harita görünümü
- **Konum Takibi**: Geolocation API ile kullanıcının mevcut konumunu otomatik algılama
- **Egzersiz Ekleme**: Harita üzerinde tıklayarak egzersiz noktaları ekleme
- **Çift Egzersiz Türü**: Koşu ve bisiklet egzersizleri için özel form alanları
- **Veri Depolama**: localStorage kullanarak egzersiz verilerini tarayıcıda kalıcı saklama
- **Responsive Tasarım**: Farklı ekran boyutlarında optimize edilmiş kullanıcı arayüzü

### Egzersiz Metrikleri

#### Koşu Egzersizleri

- Mesafe (km)
- Süre (dakika)
- Tempo (dk/km)
- Adım sayısı (adım/dk)

#### Bisiklet Egzersizleri

- Mesafe (km)
- Süre (dakika)
- Hız (km/saat)
- Yükselti kazancı (metre)

### Kullanıcı Deneyimi

- Egzersiz listesinde tıklayarak harita üzerinde o konuma otomatik geçiş
- Form validasyonu ile hatalı veri girişinin önlenmesi
- Görsel emoji ikonsları ile kullanıcı dostu arayüz
- Otomatik tarih ve saat etiketleme

## 🛠️ Kullanılan Teknolojiler

### Frontend Teknolojileri

- **HTML5**: Semantic yapı ve modern HTML özellikleri
- **CSS3**:
  - CSS Custom Properties (CSS Variables)
  - Flexbox ve Grid Layout
  - Responsive Design
  - Modern CSS özellikleri
- **Vanilla JavaScript ES6+**:
  - Class-based OOP (Object-Oriented Programming)
  - Async/Await
  - Destructuring
  - Template literals
  - Array methods (map, filter, forEach)

### Harici Kütüphaneler ve API'ler

- **Leaflet.js v1.6.0**: Interaktif harita işlevselliği
- **Google Fonts**: Manrope font ailesi
- **Geolocation API**: Kullanıcı konumu tespiti
- **Local Storage API**: Veri kalıcılığı

### Geliştirme Prensipleri

- **Object-Oriented Programming**: Workout, Running, Cycling sınıfları
- **MVC Architecture**: Model-View-Controller benzeri yapı
- **Event-Driven Programming**: Kullanıcı etkileşimleri için event listener'lar
- **Defensive Programming**: Input validation ve error handling

## 📋 Kullanım

1. **Başlangıç**: Uygulamayı açtığınızda konum izni verilmesi gerekir
2. **Egzersiz Ekleme**: Harita üzerinde egzersiz yapmak istediğiniz yere tıklayın
3. **Form Doldurma**: Açılan formda egzersiz türü ve detayları girin
4. **Kaydetme**: OK butonuna tıklayarak egzersizi kaydedin
5. **Görüntüleme**: Sol panelde egzersiz listesini görüntüleyin
6. **Navigasyon**: Listeden bir egzersize tıklayarak haritada o konuma gidin

## 📁 Proje Yapısı

```
Mapty/
├── final/                  # Tamamlanmış proje dosyaları
│   ├── index.html         # Ana HTML dosyası
│   ├── script.js          # JavaScript kodları
│   ├── style.css          # CSS stilleri
│   ├── logo.png           # Uygulama logosu
│   └── icon.png           # Favicon
├── starter/               # Başlangıç kodları
└── README.md             # Proje dokümantasyonu
```

## 🎯 Öğrenme Hedefleri

Bu proje aşağıdaki konuları öğrenmek için geliştirilmiştir:

- Modern JavaScript ES6+ özellikleri
- Object-oriented programming
- API entegrasyonu (Geolocation, Local Storage)
- Harici kütüphane kullanımı (Leaflet.js)
- Event handling ve DOM manipülasyonu
- Responsive web design
- Code organization ve best practices

## 🔧 Kurulum

1. Projeyi klonlayın veya indirin
2. `final/index.html` dosyasını bir web sunucusunda çalıştırın
3. Modern bir web tarayıcısında açın (Chrome, Firefox, Safari, Edge)
4. Konum izni verin

## 📱 Tarayıcı Desteği

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Katkıda Bulunma

Bu proje eğitim amaçlıdır. Geliştirmeler ve öneriler için pull request göndererebilirsiniz.

## 📄 Lisans

Bu proje Jonas Schmedtmann tarafından oluşturulmuş eğitim materyalidir. Öğrenme ve portfolio amaçlı kullanılabilir.

---

**Geliştirici**: Jonas Schmedtmann  
**Proje Türü**: Eğitim Projesi  
**Teknoloji**: Vanilla JavaScript  
**Seviye**: Orta/İleri
