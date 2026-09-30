# OLEARYA — görsel deposu (assets.olearya.com)

⛔ **BU DEPOYU SİLMEYİN, ADINI DEĞİŞTİRMEYİN, PRIVATE YAPMAYIN.**
`assets.olearya.com` doğrudan buraya bağlıdır. Depo silinir/gizlenirse mağazadaki
görseller kırılır.

## Ne işe yarar

OLEARYA'nın kalıcı görsel adresleri burada barındırılır. Amaç: görsellerin
web sitesinin ya da mağaza altyapısının ömründen **bağımsız** olması. Site
değişse, hosting kapansa, tema değişse bile aşağıdaki adresler çalışmaya devam eder.

| Adres | Kullanım |
|---|---|
| https://assets.olearya.com/manzara-panorama.jpg | Masaüstü ana sayfa hero (2200×1238) |
| https://assets.olearya.com/manzara-dikey.jpg | Mobil ana sayfa hero (1120×1400) |
| https://assets.olearya.com/urun-sahne.jpg | "Ayvalık'ta bir sabah" ürün görseli (1100×1100) |
| https://assets.olearya.com/kutu-250.jpg | 250 ml hediye kutusu (900×900) |
| https://assets.olearya.com/kutu-750.jpg | 750 ml hediye kutusu (900×900) |
| https://assets.olearya.com/zeytin-dali-v1.jpg | "Hasattan sofraya" bölümündeki zeytin dalı madalyonu (480×480) |
| https://assets.olearya.com/mail-imza-v6.jpg | E-posta imzası (800×200) — Zoho imzası bu adresi canlı çeker |
| https://assets.olearya.com/saha-01-zeytinlik-v1.webp | Ana sayfa saha şeridi 1/6 — zeytinlik (1200×800) |
| https://assets.olearya.com/saha-02-elle-toplama-v1.webp | Ana sayfa saha şeridi 2/6 — elle toplama (1200×800) |
| https://assets.olearya.com/saha-03-dal-v1.webp | Ana sayfa saha şeridi 3/6 — dalda yeşil zeytin (1200×800) |
| https://assets.olearya.com/saha-04-kasa-v1.webp | Ana sayfa saha şeridi 4/6 — toplanan kasalar (1200×800) |
| https://assets.olearya.com/saha-05-sikimhane-v1.webp | Ana sayfa saha şeridi 5/6 — sıkımhane (1200×800) |
| https://assets.olearya.com/saha-06-dolum-v1.webp | Ana sayfa saha şeridi 6/6 — dolum (1200×800) |

## Nasıl çalışıyor

- Dosyalar bu deponun kökünde duruyor (build yok, derleme yok, sadece dosyalar).
- GitHub Pages bunları yayınlıyor, HTTPS sertifikasını GitHub otomatik veriyor.
- `assets.olearya.com` → GoDaddy DNS'te **CNAME → avberkeerkesim.github.io**
- `CNAME` dosyası özel alan adını GitHub'a bildirir — **silinmemeli.**

## Görsel değiştirmek gerekirse

İçeriği değişen dosyanın **adını da değiştirin** (ör. `kutu-750-v2.jpg`) ve
mağazadaki bağlantıyı güncelleyin. Aynı ada yazarsanız tarayıcı/CDN eski
görseli bir süre göstermeye devam eder.

## Depolama sağlayıcısını değiştirmek gerekirse

Adresler kendi alan adımızda olduğu için sağlayıcı değişse bile **URL'ler aynı kalır**:
GoDaddy'de `assets` CNAME kaydını yeni sağlayıcıya çevirmek yeterlidir.
Mağazadaki hiçbir bağlantıya dokunulmaz.

⚠️ Burada yalnızca **herkese açık olması amaçlanan** marka görselleri durur.
Fiyat, tedarikçi, sözleşme, kişisel veri veya kimlik bilgisi bu depoya konmaz —
onlar private `zeytin` deposunda kalır.
