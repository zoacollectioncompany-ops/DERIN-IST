# Derin İstanbul Leather — Resmi Web Sitesi

**Premium deri üreticisi | Uşak üretim · İstanbul ihracat · Avrupa pazarı**

🌐 **Canlı Site:** [zoacollectioncompany-ops.github.io](https://zoacollectioncompany-ops.github.io)

---

## 📁 Dosya Yapısı

```
repository/
├── index.html        → Ana web sitesi (tüm içerik dahil)
├── showroom.mp4      → Zeytinburnu showroom tanıtım videosu
└── README.md         → Bu dosya
```

---

## 🏭 Firma Bilgileri

| | |
|---|---|
| **Marka** | Derin İstanbul Leather |
| **Tüzel Ad** | Serfa Deri İthalat İhracat San. ve Tic. Ltd. Şti. |
| **Kurucu** | Serdar Dursun |
| **Üretim** | Uşak, Türkiye |
| **Showroom** | Yeşiltepe Mah., Zeytinburnu, İstanbul |
| **Website** | www.derinistanbulleather.com |
| **Instagram** | [@derin_istanbul_leather](https://www.instagram.com/derin_istanbul_leather/) |

---

## 🗂️ Site Bölümleri

1. **Hero** — Deri doku arka planı + zoom animasyonu
2. **Hikaye** — Firma tanıtımı
3. **Koleksiyonlar** — Kuzu Derisi portföyü
4. **Showroom Videosu** — Zeytinburnu showroom turu
5. **Uşak Fabrikası** — Üretim tesisi + istatistikler
6. **Zeytinburnu Showroom** — İstanbul merkezi
7. **B2B Teklif Formu** — Google Form entegrasyonu
8. **Footer** — İletişim bilgileri

---

## ⚙️ Güncelleme Rehberi

### WhatsApp Numarası Değiştirme
`index.html` dosyasında şunu bul:
```
wa.me/905000000000
```
Kendi numaranla değiştir (90 = Türkiye):
```
wa.me/905321234567
```

### Google Form Bağlama
`index.html` dosyasında şunu bul:
```javascript
const GOOGLE_FORM_URL = '';
```
Google Forms embed linkini ekle:
```javascript
const GOOGLE_FORM_URL = 'https://docs.google.com/forms/d/e/XXXXX/viewform?embedded=true';
```

### Formspree Bağlama (alternatif)
`index.html` dosyasında şunu bul:
```
action="https://formspree.io/f/FORMSPREE_ID"
```
Kendi Formspree ID'nle değiştir:
```
action="https://formspree.io/f/xpwzgkqr"
```

### E-posta / Telefon Güncelleme
`index.html` içinde şunları ara ve değiştir:
```
info@derinistanbulleather.com
+90 212 XXX XX XX
```

---

## 🌍 Dil Sistemi (TR / EN)

Site tamamen iki dilli. Üst menüdeki **TR / EN** butonlarıyla geçiş yapılır.

Çevrilen bölümler:
- Navigasyon menüsü
- Hero başlık ve açıklama
- Tüm bölüm başlıkları
- Form etiketleri ve placeholder'lar
- Footer içeriği

---

## 🔧 Teknik Detaylar

| Özellik | Detay |
|---|---|
| **Teknoloji** | Saf HTML/CSS/JS — framework yok |
| **Fontlar** | Playfair Display + Jost (Google Fonts) |
| **Görseller** | Base64 gömülü — harici bağlantı yok |
| **Video** | `showroom.mp4` — ayrı dosya |
| **SEO** | Meta tags, Open Graph, Schema.org, Geo |
| **Favicon** | SVG inline — tarayıcı sekmesi ikonu |
| **Mobil** | Tam responsive — hamburger menü |

---

## 🚀 GitHub Pages Yayını

Bu repo **GitHub Pages** ile otomatik yayınlanır.

`main` branch'e her push'ta site güncellenir.

**Ayarlar:** Settings → Pages → Source: `GitHub Actions`

---

## 📞 İletişim

- **E-posta:** info@derinistanbulleather.com  
- **Instagram:** [@derin_istanbul_leather](https://www.instagram.com/derin_istanbul_leather/)
- **Adres:** Yeşiltepe Mah., Zeytinburnu, İstanbul / Deri OSB, Uşak, Türkiye

---

*© 2025 Derin İstanbul Leather · Serfa Deri İthalat İhracat San. ve Tic. Ltd. Şti.*
