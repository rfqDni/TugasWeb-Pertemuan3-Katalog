# 🎧 Katalog Produk Audio — Tugas Rutin 3

Tugas mata kuliah **Pemrograman Web (Pertemuan 3)** — membangun halaman **katalog produk responsif** dengan tema **Biru Galaxy** yang menampilkan produk audio: Headset, TWS, dan Earphone.

---

## 📋 Deskripsi Proyek

Halaman katalog produk ini dibuat menggunakan **HTML5** dan **CSS3 (Pure CSS, tanpa framework)** dengan pendekatan **mobile-first**. Desain mengusung tema *Biru Galaxy* — perpaduan warna biru malam, nebula, dan bintang halus yang memberi kesan modern, elegan, dan tidak norak.

Proyek ini dibuat untuk memenuhi **Tugas Rutin 3** pada mata kuliah Pemrograman Web.

---

## ✨ Fitur

Berikut fitur-fitur yang sudah diimplementasikan sesuai *requirements* tugas:

- ✅ **Mobile-first approach** — layout dimulai dari ukuran mobile, lalu ditingkatkan untuk layar besar
- ✅ **Grid responsif** — 1 kolom (mobile) → 2 kolom (tablet) → 4 kolom (desktop)
- ✅ **Minimal 3 breakpoint** — `base` (mobile), `640px` (tablet), `1024px` (desktop)
- ✅ **Navbar responsif** — menu desktop + hamburger menu di mobile
- ✅ **Card produk** — setiap card berisi gambar, kategori, judul, deskripsi, harga, dan tombol beli
- ✅ **Responsive images** — menggunakan `object-fit: contain` dan `max-width: 100%`
- ✅ **Tipografi dengan `clamp()`** — ukuran font menyesuaikan lebar viewport secara otomatis
- ✅ **Footer** — informasi copyright dan link sosial media

### 🎨 Fitur Tambahan (Bonus)
- Efek **shimmer** pada judul
- **Border gradient** saat card di-hover
- **Glow biru** lembut di belakang gambar produk
- **Scrollbar kustom** bertema galaxy
- **Animasi bintang berkelip** di background
- Mendukung **`prefers-reduced-motion`** untuk aksesibilitas

---

## 📸 Dokumentasi Testing

Berikut adalah hasil screenshot halaman katalog pada 2 ukuran layar berbeda untuk membuktikan bahwa layout sudah responsif.

### 📱 Mobile (375px)
> Layout 1 kolom, navbar berubah menjadi hamburger menu.

![Screenshot Mobile](screenshot-mobile.png)

### 💻 Desktop (1280px)
> Layout 4 kolom, navbar menampilkan menu lengkap (Home, Produk, Tentang).

![Screenshot Desktop](screenshot-desktop.png)

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Keterangan |
|---|---|
| **HTML5** | Struktur halaman |
| **CSS3 (Pure)** | Styling, layout grid, animasi |
| **JavaScript (Vanilla)** | Toggle menu hamburger di mobile |
| **Google Fonts (Inter)** | Tipografi modern |
| **CSS `clamp()`** | Tipografi responsif |
| **CSS `@media` query** | Responsive breakpoint |
| **CSS Custom Properties** | Variabel warna tema galaxy |

---

## 📁 Struktur Folder
