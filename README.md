<<<<<<< HEAD
# ♻️ EcoTrack — Landing Page

Platform digital pengelolaan sampah berbasis poin & reward.

## Struktur Folder

```
ecotrack-landing/
├── index.html        ← file utama (1 halaman)
├── css/
│   └── style.css     ← semua styling
├── images/
│   ├── logo-ecotrack.svg
│   └── hero-illustration.png
└── README.md
```

## Pembagian Tugas

| Anggota | Branch | Section |
|---------|--------|---------|
| Anggota 1 | `feature/hero` | `<header>` + `#hero` + setup repo |
| Anggota 2 | `feature/features` | `#features` (6 card) |
| Anggota 3 | `feature/how-it-works` | `#how-it-works` + `#cta` form |
| Anggota 4 | `feature/footer-css` | `<footer>` + CSS `:root` + media queries |

## Alur Kerja Git

```bash
# Setiap anggota — mulai dari sini
git clone https://github.com/username/ecotrack-landing.git
cd ecotrack-landing
git checkout dev
git pull origin dev
git checkout -b feature/nama-section

# Setelah selesai
git add .
git commit -m "feat: deskripsi singkat perubahan"
git push origin feature/nama-section
# → Buka Pull Request ke branch dev di GitHub
```

## Spesifikasi Teknis

- HTML5 valid (cek di https://validator.w3.org)
- Semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`
- CSS external di `css/style.css` — tidak boleh inline
- Responsif: mobile (480px), tablet (768px), desktop (1024px+)
- Deploy via GitHub Pages (branch: master)

## Live URL

> https://username.github.io/ecotrack-landing
=======
Masalah yang Ingin Diselesaikan

Indonesia menghadapi krisis pengelolaan sampah — bukan karena tidak ada tempat sampah, tapi karena kurangnya partisipasi dan edukasi masyarakat yang terstruktur.
😰 Pain Points Utama

    Masyarakat tidak tahu cara memilah sampah dengan benar.
    Tidak ada insentif nyata untuk berpartisipasi aktif.
    Titik pembuangan sampah sulit ditemukan.
    Kontribusi individu tidak tercatat, sehingga tidak terasa berdampak.
    Kurangnya edukasi visual mengenai dampak lingkungan.

💡 Solusi: EcoTrack

Platform berbasis web yang mengintegrasikan:

    Sistem poin & reward untuk memotivasi partisipasi.
    Dokumentasi kontribusi via foto upload.
    Peta lokasi pembuangan sampah.
    Konten edukasi jenis & dampak sampah.

🔑 6 Fitur Utama Platform
1
Upload Foto Sampah — dokumentasi kontribusi nyata pengguna.
2
Sistem Poin — kumpulkan poin dari setiap aktivitas pemilahan.
3
Redeem Reward — tukarkan poin dengan hadiah dan insentif menarik.
4
Edukasi Sampah — konten jenis sampah, cara kelola, dan dampak lingkungan.
5
Lapor Titik Sampah — pelaporan penumpukan sampah berbasis lokasi.
6
Peta Pembuangan — info lokasi & mekanisme pembuangan resmi.

⭐
Fitur Section

6 fitur utama dengan ikon, judul singkat, dan deskripsi pendek

# Color System — Living Archive

## 🌿 Primary — Deep Forest
Base: #154212

- PRIMARY/50  → #EBECE7
- PRIMARY/100 → #D1D9CE
- PRIMARY/200 → #A3B39F
- PRIMARY/300 → #758D6F
- PRIMARY/400 → #47673F
- PRIMARY/500 → #154212  ← Base
- PRIMARY/600 → #123B10
- PRIMARY/700 → #0E340D
- PRIMARY/800 → #0B2D0B
- PRIMARY/900 → #082608

---

## 🌱 Secondary — Veridian Leaf
Base: #2D5A27

- SECONDARY/50  → #EBEEE A
- SECONDARY/100 → #D7DDD5
- SECONDARY/200 → #B0C8AA
- SECONDARY/300 → #89B380
- SECONDARY/400 → #627A56
- SECONDARY/500 → #2D5A27  ← Base
- SECONDARY/600 → #285123
- SECONDARY/700 → #23481F
- SECONDARY/800 → #1E3F1B
- SECONDARY/900 → #193617

---

## 🌫 Neutral — Mist Gray
Base: #72796E

- NEUTRAL/50  → #F1F2F0
- NEUTRAL/100 → #E2E4E1
- NEUTRAL/200 → #C5C9C3
- NEUTRAL/300 → #A8AEA5
- NEUTRAL/400 → #8C9388
- NEUTRAL/500 → #72796E  ← Base
- NEUTRAL/600 → #61675D
- NEUTRAL/700 → #50554C
- NEUTRAL/800 → #3F433C
- NEUTRAL/900 → #2F312B

---

## 🌿 Accent / Supporting

- Deep Forest (Primary Anchor) → #154212
- Verdian Leaf (Secondary CTA) → #3C6A00
- Sapling Green (Highlight) → #BCF0AE

---

## 🪵 Neutral Surfaces

- Parchment → #FAFAF5
- Bone → #F0F0E9
- Charcoal → #1C1E1C
- Mist → #72796E

---

## 🚦 Semantic Colors

- Success → #4CAF50 (suggested green)
- Error → #E53935
- Info / Actionable → #8BC34A

---

## 🧠 Token Naming Reference

- `primary-*` → Brand / CTA / Headers
- `secondary-*` → Supporting UI / Data viz
- `neutral-*` → Backgrounds / Text / Borders
- `semantic-*` → Feedback states
>>>>>>> 5686c02 (feature: feature section)
