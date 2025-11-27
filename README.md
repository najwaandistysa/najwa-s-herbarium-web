# 🌿 Najwa's Herbarium Web: E-commerce & Edukasi Herbal Terpadu

<p align="center">
  <img src="https://raw.githubusercontent.com/najwaandistysa/najwa-s-herbarium-web/main/assets/img/logoApotek.png" alt="Logo Najwa's Herbarium" width="150">
</p>

Najwa's Herbarium adalah *template* *website* *front-end* statis yang dirancang khusus untuk platform E-commerce produk herbal, suplemen alami, dan edukasi kesehatan. Proyek ini mengimplementasikan Bootstrap 5 secara ekstensif untuk mencapai desain modern, *mobile-first*, dan memastikan konsistensi visual di seluruh halaman.

## 🌟 Fitur Inti dan Filosofi Desain (Konsistensi Global)

Filosofi desain proyek ini adalah **"Keselarasan Sudut dan Aksi"**. Semua elemen interaktif memiliki gaya yang seragam untuk menciptakan pengalaman pengguna yang mulus dan profesional.

### 1. Konsistensi Visual Menyeluruh
* **Card Uniformity:** Semua elemen Card di seluruh website (Produk, Kategori, Blog, Fitur 'Mengapa Memilih Kami', dan Banner Konsultasi) menggunakan radius sudut yang seragam yaitu **`border-radius: 1.25rem`**.
* **Efek Hover Premium:** Setiap Card memiliki efek mengangkat halus (`transform: translateY(-5px)`) dan bayangan tegas saat di-hover, memberikan kesan interaktif dan kualitas tinggi.

### 2. Konsistensi Tombol (Pill-shaped Outline)
* **Gaya Seragam:** Seluruh tombol interaktif (Tombol Navbar, Tombol Filter, Tombol "Lihat Detail & Beli") menggunakan gaya **Outline Dark Cyan** berbentuk **Pil (`rounded-pill`)**.
* **Transisi:** Tombol akan berubah menjadi warna solid Dark Cyan saat di-*hover*, memberikan umpan balik visual yang jelas kepada pengguna.

### 3. Solusi Tata Letak Vertikal
* **Penyelarasan Rata Bawah:** Tombol aksi pada Card Jurnal atau Produk secara otomatis disejajarkan rata bawah (`mt-auto` dengan Flexbox) untuk mengatasi perbedaan tinggi teks deskripsi, memastikan tampilan grid yang rapi.
* **Centering Konten Kategori:** Konten di dalam Card Kategori sudah disempurnakan menggunakan Flexbox agar ikon dan teks selalu terpusat sempurna.

### 4. Komponen Fungsionalitas E-commerce
* **Navigasi Lintas Halaman:** Navbar fungsional terpasang di semua halaman (Beranda, Produk & Layanan, Tentang Kami, Blog/Edukasi, Kontak).
* **Interaksi Cepat:** Integrasi **Modal Pencarian** dan **Offcanvas Keranjang Belanja** yang dapat diakses dengan cepat dari Navbar.
* **Detail Produk Lengkap:** Halaman detail produk menggunakan komponen **Tabs** untuk membagi informasi menjadi Deskripsi, Ulasan, dan Cara Pakai yang terstruktur.

## 💻 Detail Teknologi dan Dependensi

| Teknologi | Versi | Peran Utama |
| :--- | :--- | :--- |
| **HTML5 & CSS3** | Terbaru | Struktur konten dan *styling* dasar. |
| **Bootstrap** | v5.x | Kerangka kerja *front-end* utama (grid, komponen, utilitas). |
| **Font Awesome** | v6.x | Penyedia ikon yang digunakan secara luas di seluruh situs. |
| **Custom Styling** | `style.css` | Mendefinisikan tema warna (`--secondary-color`), *hover*, dan konsistensi radius sudut Card. |

### Dependensi Kode (Lokal)
Semua aset dimuat secara lokal dari folder `assets/`.
* `assets/css/bootstrap.min.css`
* `assets/css/all.min.css` (Font Awesome CSS)
* `assets/js/bootstrap.bundle.min.js` (JavaScript Bootstrap)

## 🚀 Panduan Instalasi Cepat

Proyek ini 100% statis. Ikuti langkah di bawah ini untuk menjalankannya.

### 1. Kloning Repositori

```bash
git clone [https://github.com/najwaandistysa/najwa-s-herbarium-web.git](https://github.com/najwaandistysa/najwa-s-herbarium-web.git)
cd najwa-s-herbarium-web
