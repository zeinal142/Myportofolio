# Personal Portfolio Website 

Website portfolio pribadi yang responsif, modern, dan dilengkapi dengan formulir kontak yang berfungsi penuh. Proyek ini dibangun menggunakan **Bootstrap 5** untuk styling dan **EmailJS** untuk pengiriman pesan email secara *serverless* (tanpa backend PHP/Node.js).

![Tech Stack](https://img.shields.io/badge/Tech-HTML5-orange) ![Tech Stack](https://img.shields.io/badge/Style-Bootstrap%205-purple) ![Tech Stack](https://img.shields.io/badge/Email-EmailJS-green)

## 📋 Fitur Utama

* **Desain Responsif:** Tampilan menyesuaikan dengan sempurna di Desktop, Tablet, dan Mobile (menggunakan Bootstrap Grid).
* **Working Contact Form:** Formulir kontak aktif yang mengirim pesan langsung ke email pemilik.
* **Notifikasi Real-time:** Pengguna mendapat notifikasi alert saat pesan sedang dikirim, sukses, atau gagal.
* **Social Media Links:** Integrasi ikon FontAwesome untuk tautan profesional (LinkedIn, GitHub, Instagram).

## 🛠️ Teknologi yang Digunakan

* **HTML5:** Struktur utama halaman web.
* **CSS / Bootstrap 5.3:** Framework CSS untuk layout grid, komponen card, dan styling utilitas (`bg-primary`, `shadow-lg`, dll).
* **FontAwesome:** Untuk ikon sosial media dan ikon pesawat kertas.
* **EmailJS SDK:** Library JavaScript pihak ketiga untuk menghubungkan form HTML dengan layanan email.

## ⚙️ Konfigurasi & Instalasi

Karena ini adalah website statis, Anda tidak perlu menginstal server. Cukup buka file `index.html` di browser.

### Langkah Penting: Mengaktifkan EmailJS

Agar formulir kontak berfungsi, Anda harus menghubungkannya dengan akun EmailJS Anda.

1.  Daftar di [EmailJS](https://www.emailjs.com/).
2.  Buat **Email Service** (pilih Gmail) dan **Email Template**.
3.  Buka file `index.html` (atau file script Anda).
4.  Cari bagian script di bawah dan ganti dengan kredensial Anda:

```javascript
// Ganti dengan Public Key Anda
emailjs.init("PUBLIC_KEY_ANDA"); 

// ... di dalam event listener ...
const serviceID = 'SERVICE_ID_ANDA';
const templateID = 'TEMPLATE_ID_ANDA';
