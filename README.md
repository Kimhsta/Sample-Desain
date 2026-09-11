# Sample-Desain

Koleksi resource desain grafis dan UI — termasuk font, efek visual, tekstur, dan elemen grafis untuk kebutuhan desain.

## Struktur Project

```
Sample-Desain/
├── FiraCode/                 # FiraCode Nerd Font (monospace, v6.2)
├── Fonts/                    # Koleksi font (~80+ file .ttf)
│   ├── font kaos/            # Font untuk desain kaos
│   ├── font logo/            # Font untuk logo
│   └── Source code/          # Source file font (.zip)
├── My Resource V1/           # Aset grafis versi 1
│   ├── LENSFLARE/            # Efek lens flare
│   ├── NATURE/               # Asset bertema alam
│   └── Toing GFX PACK/       # Brush pack untuk thumbnail YouTube
├── My Resource V2/           # Aset grafis versi 2 (lebih lengkap)
│   ├── EFFECT/               # Efek visual (smoke, glass, chroma, glow)
│   ├── HUD/                  # Elemen HUD / antarmuka futuristik
│   ├── LETTER/               # Tipografi stilis A-Z
│   ├── LIGHTNING/            # Efek petir / listrik
│   ├── MEMPHIS PNG/          # Elemen gaya Memphis
│   ├── New Icon/             # Set ikon
│   ├── OTHER/                # Referensi lain (space UI, infografis)
│   ├── Particles/            # Efek partikel
│   ├── PLANET/               # Gambar planet (Mercury - Pluto)
│   └── PNG/                  # Aset PNG umum
└── Texture/                  # Tekstur latar belakang
    ├── TEXTURE/              # Koleksi tekstur (~118 file)
    └── TEXTURE V2/           # Koleksi tekstur versi 2 (~61 file)
```

## Fitur

| Kategori | Deskripsi |
|----------|-----------|
| **Typography** | 16+ family font (static & variable), mendukung script Latin, Vietnam, Arab |
| **Nerd Font** | FiraCode — monospace dengan icon glyphs, cocok untuk terminal & desain tech |
| **Lens Flare** | ~40 overlay lens flare untuk komposisi sinematik |
| **Visual Effects** | ~160 gambar efek: smoke, broken glass, chroma, glow, abstrak |
| **HUD Elements** | ~35 elemen antarmuka futuristik / heads-up display |
| **Lightning** | Overlay efek petir / listrik |
| **Memphis** | 10 elemen gaya Memphis (geometris bold) |
| **Particles** | Efek partikel untuk efek atmosferik |
| **Planets** | Gambar PNG planet berkualitas tinggi (9 planet) |
| **Textures** | ~180 tekstur latar: overlay, grunge, broken glass, abstrak |
| **Icons** | Set ikon dalam berbagai gaya |

## Cara Menggunakan

### Font

**macOS:**
```bash
cp Fonts/*.ttf ~/Library/Fonts/
```

**Linux:**
```bash
cp Fonts/*.ttf ~/.local/share/fonts/
fc-cache -fv
```

**Windows:**
Klik kanan file `.ttf` → Install.

### Aset Grafis

Import langsung ke tools desain kamu:
- **Photoshop** — Drag & drop ke canvas
- **Affinity Designer** — File → Place
- **Figma** — Drag ke Assets panel
- **Canva** → Upload →拖 ke desain

### Inkscape Quran Extension

```bash
pip install alquran-id
cp Fonts/font logo/inkscape-quran-id/inkscape-quran-id-master/{quran.inx,quran.py} ~/.config/inkscape/extensions/
```

## Lisensi

Koleksi ini bersifat personal. Lisensi individual font dan aset dapat dilihat pada file `OFL.txt` atau README masing-masing di dalam folder terkait.

---

Dibuat oleh kiki-mahesta
