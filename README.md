# Karaca Gold — Brüksel

Av. Rogier 215, 1030 Schaerbeek, Brussels — 22 ayar Anadolu altını vitrin sitesi.

## Yapı

```
karacagold/
├── index.html              # Tek sayfa, tüm site
├── logo.png                # Logo (favicon + nav + footer)
├── logo-transparent.png    # Şeffaf logo
├── logo.pdf                # Vektör logo
├── karacashowroom.jpg/png  # Atölye fotoğrafı
├── imgkaraca/              # Set ürün fotoğrafları (4 set + 5 bilezik)
├── imgkolye/               # Kolye galerisi (8 model)
└── yuzukvebilezik/         # Yüzük + küpe + ek bilezikler
```

## Bölümler

| ID | Bölüm | İçerik |
|----|-------|--------|
| `#atelier` | Atölye | Showroom fotoğrafı + hakkında |
| `#collections` | Setler | 4 tam set (Hint İşi, Baget Taşlı, Trabzon Hasırı, Damla Model) |
| `#bilezik` | Bilezikler | 12 model |
| `#kolye` | Kolyeler | 8 model |
| `#yuzuk` | Yüzük & Küpe | 3 model |
| `#craft` | Süreç | 4 adımlı ziyaret deneyimi |
| `#reviews` | Yorumlar | Google 5★ yorumları |
| `#visit` | Ziyaret | Harita + saatler + iletişim |

## Yeni ürün/foto eklemek

**Bilezik / Kolye / Yüzük galerisine:**
1. Görseli ilgili klasöre koy (`imgkaraca/`, `imgkolye/`, `yuzukvebilezik/`)
2. `index.html` içinde ilgili `<div class="kolye-grid">` bloğuna yeni `<div class="kolye-item">` ekle
3. Sayfa altındaki JS dizisine (`bilezikImgs` / `kolyeImgs` / `yuzukImgs`) görsel yolunu ekle

**Yeni set kartı eklemek:**
- `index.html` içinde `const products = [...]` dizisine yeni nesne ekle: `{n, t, p, c, img}`

## Yerelde çalıştırma

`index.html`'e çift tıkla — direkt tarayıcıda açılır. Veya:

```
python -m http.server 8000
```

## Yayına alma seçenekleri

1. **GitHub Pages** (ücretsiz, kolay) — Repo Settings → Pages → Source: main → Save
2. **Netlify / Vercel** (ücretsiz, daha hızlı) — Repo'yu bağla, otomatik deploy
3. **Kendi domain** — yukarıdakilerden birine custom domain bağla

## İletişim bilgileri

- **Telefon:** 0486 64 79 07
- **Adres:** Av. Rogier 215, 1030 Schaerbeek, Brussels
- **Saatler:** Pzt-Sl, Per-Pz 10:30–18:30 · Çarşamba kapalı
