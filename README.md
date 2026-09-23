# Kampüs Etkinlikleri - Sprint 1

Bu proje, Kampüs Etkinlikleri uygulamasının iskeletini **yalnızca HTML** (CSS ve JavaScript kullanılmadan) kullanılarak semantik etiketlerle oluşturulmuş versiyonudur.

## Proje Yapısı

- `index.html`: Ana sayfa, uygulama hakkında bilgi ve yaklaşan etkinlikler özeti.
- `etkinlikler.html`: Tüm etkinliklerin tek sütunlu tablo kart yapısında listesi ve ayın programı özeti.
- `etkinlik-detay.html`: Seçilen etkinliğin afişi, künye detayları ve açıklaması.
- `etkinlik-ekle.html`: Yeni etkinlik ekleme formu (semantic form elemanları ve `required` kontrolleri ile).
- `etkinlik-guncelle.html`: Mevcut etkinliği güncelleme formu (doldurulmuş varsayılan değerler ile).
- `afis.jpg`: Etkinlik detay sayfasında kullanılan görsel.

## Özellikler & Semantik HTML Yapısı

- Her sayfada ortak `<header>`, `<nav>`, `<main>` ve `<footer>` iskeleti kullanılmıştır.
- Her sayfada hiyerarşiye uygun yalnızca **bir adet `<h1>`** başlık bulunur.
- Tüm form alanları görünür `<label>` elemanlarına sahiptir ve `required` doğrulama özniteliği içerir.
- Etkinlik listeleri `<table border="1">` ve `<caption>` elemanları ile semantik olarak yapılandırılmıştır.
- Detay sayfasında `<figure>`, `<figcaption>`, `<dl>`, `<dt>`, `<dd>` ve `<time>` etiketleri kullanılmıştır.
- Projede herhangi bir CSS veya JavaScript dosyası/kodu kullanılmamıştır.

## Canlı Adres (Vercel)

- **Vercel Live URL:** [https://sprint-01-gamma.vercel.app](https://sprint-01-gamma.vercel.app)

## Git ve Sürüm

- **Git Tag:** `sprint-01`
