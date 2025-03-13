# jQuery ile Hava Durumu Uygulaması

Bu proje, jQuery kullanarak geliştirilmiş dinamik bir hava durumu uygulamasıdır. Kullanıcılar şehir ismi girerek anlık hava durumu bilgilerini görüntüleyebilirler.

## Özellikler

- Şehir ismine göre hava durumu sorgulama
- Sıcaklık, nem, rüzgar hızı ve hava durumu bilgilerini gösterme
- Hava durumuna göre değişen görsel gösterimler
- Konum tabanlı otomatik hava durumu gösterimi (HTML5 Geolocation API)
- Son aranan şehirlerin kaydedilmesi (localStorage)
- Hata durumlarında kullanıcı bildirimleri

## Kullanılan Teknolojiler

- HTML5
- CSS3
- jQuery
- AJAX
- OpenWeatherMap API
- HTML5 Geolocation API
- LocalStorage

## Proje Yapısı

      weather-app/
      ├── index.html
      ├── style.css
      └── script.js

## Nasıl Kullanılır

1. Arama kutusuna bir şehir adı girin
2. "Hava Durumunu Göster" butonuna tıklayın
3. Şehrin güncel hava durumu bilgileri ekranda görüntülenecektir
4. Konumunuzu paylaşmak isterseniz "Konumumu Kullan" butonuna tıklayabilirsiniz

## API Anahtarı

Bu uygulama OpenWeatherMap API'sini kullanmaktadır. API anahtarı `script.js` dosyasında tanımlanmıştır:

![WhatsApp Görsel 2025-03-13 saat 21 43 52_5ba3d48a](https://github.com/user-attachments/assets/b167a5e4-764f-4756-9c6b-1ce38b89f311)

