# Portfolio Website: Hitori Gotoh (Bocchi)

## Preview Tampilan

### 1. Landing Page (`index.html`)
Halaman utama yang memuat perkenalan singkat, hero section dengan foto polaroid interaktif, kartu profil Bocchi, serta banner kutipan dengan stiker animasi GIF transparan.

![Landing Page](assets/screenshots/landing-page.png)

---

### 2. Gallery (`gallery.html`)
Menyajikan etalase karya dan dokumentasi penampilan panggung Kessoku Band dalam format kartu interaktif, pill minat/skills, serta tabel jadwal latihan band.

![Gallery](assets/screenshots/gallery.png)

---

### 3. Creative CV (`cv.html`)
Menampilkan Curriculum Vitae kreatif dan interaktif yang mencakup ringkasan statistik karakter, lini masa (*timeline*) pengalaman dan pendidikan, bilah kemampuan (*skills bar*) dengan indikator persentase, serta formulir kontak interaktif.

![Creative CV](assets/screenshots/cv.png)

---

## Fitur Utama

Website ini dibangun murni menggunakan **HTML5 semantik** dan **CSS3 modern** dengan beberapa fitur nilai tambah:

1. **Native from Scratch (No Framework)**
   * Dibuat 100% murni tanpa Tailwind, Bootstrap, atau library UI lainnya.
2. **Desain Responsif Penuh (*Fully Responsive*)**
   * Menggunakan CSS Flexbox, CSS Grid, dan Media Queries untuk menyesuaikan tata letak pada layar **Desktop**, **Tablet ($\le 768\text{px}$)**, dan **Mobile Smartphone ($\le 480\text{px}$)**.
3. **Pure CSS Hamburger Navigation (No JavaScript)**
   * Menu navigasi responsif pada perangkat mobile dibangun murni menggunakan teknik *checkbox hack* (`#menu-toggle:checked ~ .nav-links`) tanpa sebaris kode JavaScript pun.
4. **Efek Kertas Sobek (*Torn Paper Edge*)**
   * Menggunakan `clip-path: polygon(...)` dinamis untuk menghasilkan efek gerigi sobekan kertas yang menyatu mulus di atas footer pada setiap halaman.
5. **Komponen Scrapbook Neo-Brutalis Kustom**
   * Stempel angka transparan (`.stamp`), stiker selotip miring (`.tape`), kartu polaroid dengan pin pick gitar, dan tombol 3D offset lift saat di-hover.
6. **Interactive Skills Progress Track**
   * Bilah keahlian pada CV yang memisahkan label teks dan persentase dengan *track bar* berbayang dalam (*inset shadow*) dan warna tema yang kontras.
7. **Formulir Kontak Terstruktur**
   * Form kontak interaktif dengan validasi atribut HTML5 (`required`, `type="email"`, dll.) dan visual *focus-state* yang jelas.
8. **Ikon Vektor Mandiri & Aset Ringan**
   * Ikon media sosial menggunakan file SVG mandiri di dalam folder `assets/icons/` yang dilengkapi efek filter transisi warna otomatis saat disentuh kursor.

---

## Struktur Repo

```text
pweb-html_css-c12-2026/
├── assets/
│   ├── icons/
│   │   ├── github.svg
│   │   ├── instagram.svg
│   │   ├── tsuchinoko-bocchi.png
│   │   ├── twitter.svg
│   │   └── youtube.svg
│   ├── images/
│   │   ├── bocchi.gif
│   │   ├── bocchi-profile.webp
│   │   ├── first-record.avif
│   │   ├── school-concert.jpg
│   │   ├── school-concert_2.webp
│   │   └── starry-first-live.jpg
│   └── screenshots/
│       ├── cv.png
│       ├── gallery.png
│       └── landing-page.png
├── css/
│   └── style.css
├── cv.html
├── gallery.html
├── index.html
└── README.md
```


