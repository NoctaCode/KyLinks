# KyLinks 🚀

KyLinks adalah aplikasi web *profile hub* (seperti Linktree) personal dengan desain ultra-modern berbasis **Glassmorphism** dan tema **Neon Cyberpunk**. Aplikasi ini dirancang agar ringan, responsif, dan dapat diinstal sebagai **PWA (Progressive Web App)** langsung ke perangkat pengguna.

## ✨ Fitur Utama

- **Desain Ultra-Modern & Glassmorphism**: Menggunakan perpaduan warna gradasi neon cyberpunk yang memanjakan mata.
- **PWA Ready**: Dilengkapi dengan manifest JSON bawaan agar aplikasi bisa diinstal di Android/iOS/Desktop.
- **Terminal Kontrol (Admin Dashboard)**: Panel rahasia yang terintegrasi langsung (akses menggunakan kata sandi bawaan) untuk mengelola data profil dan tautan tanpa *database* eksternal.
- **Sistem Kategori & Pencarian**: Tautan otomatis dikelompokkan berdasarkan kategori, serta dilengkapi *live search bar* untuk mencari tautan dengan cepat.
- **Statistik Klik Riil**: Memantau jumlah total klik keseluruhan maupun jumlah klik pada setiap tautan secara spesifik.
- **Manajemen Gambar Lokal (Base64)**: Pengguna dapat mengunggah foto profil langsung dari penyimpanan internal perangkat, yang nantinya dikonversi otomatis menjadi format Base64.
- **Fitur Prioritas & Favorit**: Mendukung penyematan (*pinning*) tautan utama agar tampil di bagian paling atas.
- **Generator QR Code & Berbagi Cepat**: Terintegrasi dengan QRCode.js untuk membagikan tautan profil melalui kode QR serta integrasi *Web Share API*.
- **Tanpa Database (Client-Side)**: Semua data disimpan secara aman langsung di dalam `localStorage` browser pengguna, lengkap dengan fitur **Backup & Restore** data berupa file `.json`.

## 🛠️ Teknologi yang Digunakan

- HTML5 & CSS Kustom (Efek Glassmorphism & Animasi)
- **Tailwind CSS v4** (via browser CDN)
- **FontAwesome v6.6.0** (untuk ikon-ikon menarik)
- **QRCode.js** (untuk pembuatan kode QR secara instan)

## 🔑 Akses Terminal Kontrol (Admin)

Untuk masuk ke **Terminal Kontrol** dan mengubah identitas profil (Nama, Bio, Foto, Lokasi) atau memanipulasi komponen link:
1. Klik tombol **Terminal Kontrol** di bagian bawah profil.
2. Masukkan sandi akses default bawaan:
   ```text

   Nocta-Code
