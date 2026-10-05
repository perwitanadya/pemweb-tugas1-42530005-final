  # Portofolio Software Developer: Nakeya Canakia

Tugas 1 Pemrograman Web: Rancang Bangun Responsive Landing Page Berbasis Dokumen Semantik HTML5 dan Tata Letak CSS Modern.

| | |
|---|---|
| **Nama** | Komang Widya Paramitha |
| **NIM** | 42530005 |
| **Program Studi** | S1 Teknologi Informasi |
| **Tema** | Tema C: Portofolio Profesional Pengembang Perangkat Lunak |

## Live Preview

 https://perwitanadya.github.io/pemweb-tugas1-42530005-final/

## Deskripsi

Landing page satu halaman yang menampilkan profil, proyek unggulan, keahlian dan tech stack, sertifikasi, serta formulir kontak. Dibangun dari nol tanpa framework CSS (tanpa Bootstrap, Tailwind, atau Bulma).

## Fitur

- **HTML5 semantik:** `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, tanpa div-soup
- **Aksesibilitas (WCAG 2.1):** skip link, `aria-label` pada navigasi dan formulir, teks `alt` deskriptif, label pada setiap input, hierarki heading runtut (h1 sampai h4), fokus keyboard yang jelas
- **CSS modern:** Flexbox untuk navigasi, tombol, dan tag; CSS Grid untuk layout bagian dan kartu (`repeat(auto-fit, minmax(...))`)
- **Mobile-first:** breakpoint `min-width: 768px` (tablet) dan `min-width: 1024px` (desktop)
- **Tanpa horizontal overflow** pada lebar 320px sampai 1920px
- **CSS Custom Properties** untuk palet warna dan font
- **Efek interaktif:** kartu proyek, kartu sertifikat, dan tech stack naik saat di-hover atau disentuh
- **Formulir kontak** terhubung ke Formspree sehingga pesan terkirim tanpa aplikasi email

## Teknologi

HTML5, CSS3, font Montserrat (Google Fonts), Formspree, Git, GitHub Pages.

## Struktur Proyek

```
pemweb-tugas1-42530005/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

## Cara Menjalankan

1. Clone repositori ini atau unduh sebagai ZIP.
2. Buka `index.html` di browser, atau gunakan ekstensi Live Server di VS Code.

## Hasil Pengujian

- Validasi W3C HTML: lolos tanpa error
- Skor aksesibilitas Lighthouse: 100
- Uji responsif: 320px, 375px, 768px, 1280px, dan 1920px tanpa scroll horizontal
