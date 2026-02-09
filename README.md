# Template Website Ekspedisi

Template website profil perusahaan ekspedisi modern dengan desain premium dan responsive.

## Fitur

- **Desain Modern & Premium** - Tampilan profesional dengan warna oranye yang menarik
- **Single Page Application** - Navigasi smooth scroll ke setiap section
- **Responsive & Mobile Friendly** - Tampilan optimal di desktop, tablet, dan mobile
- **Form Kontak WhatsApp** - Formulir terintegrasi langsung dengan WhatsApp Web
- **Section Lengkap:**
  - Hero Section dengan statistik
  - Tentang Kami
  - Layanan (Cargo, Express, Warehousing)
  - Keunggulan & Statistik
  - Testimoni Klien
  - Form Kontak
  - Footer dengan Media Sosial

## Teknologi

- **HTML5** - Struktur semantic
- **Bootstrap 5.3.2** - Framework CSS (local file)
- **Alpine.js** - JavaScript framework ringan (local file)
- **Custom CSS** - Styling tambahan
- **Google Fonts** - Typography

## Struktur File

```
ekspedisi/
├── index.html                      # File utama website
├── README.md                       # Dokumentasi ini
└── assets/
    ├── css/
    │   ├── bootstrap.min.css       # Bootstrap CSS framework
    │   └── custom.css              # Custom styles
    ├── js/
    │   └── alpine.min.js           # Alpine.js framework
    └── img/
        ├── hero-truck.jpg          # Hero image
        ├── service-cargo.jpg       # Service image 1
        ├── service-delivery.jpg    # Service image 2
        ├── service-warehouse.jpg   # Service image 3
        ├── testimonial-1.jpg       # Testimonial avatar 1
        ├── testimonial-2.jpg       # Testimonial avatar 2
        └── testimonial-3.jpg       # Testimonial avatar 3
```

## Konfigurasi

### Konfigurasi WhatsApp

Ubah nomor WhatsApp di bagian script (line ~480):
```
const phoneNumber = '6281234567890'; // Ganti dengan nomor WhatsApp bisnis Anda
```

### Ganti Gambar

Replace file di folder `assets/img/` dengan gambar Anda sendiri. Pastikan:
- Format: JPG
- Ukuran hero: 1920x1080px (landscape)
- Ukuran service: 800x600px (landscape)
- Ukuran testimonial: 200x200px (square)

### Edit Konten

Buka `index.html` dan edit teks sesuai kebutuhan:
- Nama perusahaan (line 14, 45, dll)
- Informasi kontak (alamat, telepon, email)
- Deskripsi layanan
- Testimoni

## Kustomisasi

### Warna Brand

Edit variabel di `assets/css/custom.css`:
```
:root {
    --primary-color: #FF6B35;    /* Warna utama */
    --primary-dark: #E55A28;     /* Warna hover */
    --secondary-color: #1a1a2e;  /* Warna gelap */
}
```

### Menu Navigasi

Tambah/hapus menu di bagian navbar (line ~29-35):
```
<li class="nav-item">
    <a class="nav-link" href="#section-id">Nama Menu</a>
</li>
```

