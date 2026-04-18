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