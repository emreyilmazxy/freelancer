# Freelancer Portfolio Website

Modern ve duyarlı (responsive) bir freelancer portföy web sitesi. SCSS, jQuery ve modern web teknolojileri kullanılarak geliştirilmiştir.

![Proje Önizleme](public/img/main-background-promote)

## 🚀 Özellikler

- Tamamen duyarlı (responsive) tasarım
- Modern ve temiz arayüz
- SCSS ile modüler CSS yapısı
- Smooth scroll özelliği
- Owl Carousel ile referans slider'ı
- Lightbox ile proje görsellerini görüntüleme
- Animasyonlu yazı efekti (Typewriter)
- Font Awesome ikonları
- Animate.css ile sayfa animasyonları

## 🛠️ Kullanılan Teknolojiler

- HTML5
- SCSS/CSS3
- JavaScript
- jQuery
- Owl Carousel
- Font Awesome
- Animate.css
- Lightbox.js
- Google Fonts

## 📂 Proje Yapısı

```
freelancer/
├── public/
│   ├── css/
│   ├── img/
│   ├── js/
│   ├── about.html
│   ├── contact.html
│   ├── index.html
│   └── projects.html
├── scss/
│   ├── _about.scss
│   ├── _base.scss
│   ├── _contact.scss
│   ├── _footer.scss
│   ├── _header.scss
│   ├── _home.scss
│   ├── _mobile.scss
│   ├── _projects.scss
│   ├── _utilities.scss
│   ├── _variables.scss
│   └── main.scss
├── package.json
└── README.md
```

## 🎨 SCSS Vurguları

- **Modüler Yapı**: Her bileşen için ayrı SCSS dosyası
- **Değişkenler**: `_variables.scss` ile merkezi renk ve boyut yönetimi
- **Utility Classes**: `_utilities.scss` ile yeniden kullanılabilir stiller
- **BEM Metodolojisi**: Block Element Modifier yaklaşımı ile CSS organizasyonu
- **Responsive Design**: `_mobile.scss` ile mobil uyumlu tasarım
- **Grid System**: Modern CSS Grid sistemi kullanımı

## 🛠️ Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/your-username/freelancer.git
```

2. Bağımlılıkları yükleyin:
```bash
npm install
```

3. SCSS'i derlemek için:
```bash
npm run scss
```

## 💻 Geliştirme

SCSS dosyalarında değişiklik yapmak için watch modunu kullanın:

```bash
npm run scss
```

Bu komut SCSS dosyalarını izleyecek ve değişiklikleri otomatik olarak CSS'e derleyecektir.

## 📱 Responsive Tasarım

- Mobile-first yaklaşım
- Esnek grid sistemi
- Duyarlı görüntüler ve videolar
- Özelleştirilmiş mobil menü
- Breakpoint'ler için SCSS mixin'leri

## 🎯 Önemli SCSS Özellikleri

```scss
// Değişkenler
$primary-color: #ef6d6d;
$light-color: #f5f5f5;
$dark-color: #333;
$medium-color: #ccc;
$max-width: 1200px;

// Mixins
@mixin mediaXl {
  @media screen and (min-width: 1600px) {
    @content;
  }
}

// Placeholder Selectors
%btn-shared {
  display: inline-block;
  padding: .7rem 2rem;
  transition: all .3s;
  border: none;
  cursor: pointer;
}
```

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 👨‍💻 Yazar

[emre yılmaz] - [@emreyilmazxy](https://github.com/emreyilmazxy)
