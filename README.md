# Sistem Informasi Perpustakaan QR Code - Kelompok 9

## Identitas Kelompok

- Nama Kelompok: Kelompok 9
- Anggota:
  - Abubakar Shiddiq (F55124036)
  - Fiqhy Fauzan (F55124029)
  - Gina Masita (F55124032)

## Deskripsi Singkat

Sistem Informasi Perpustakaan berbasis CodeIgniter 4 dengan fitur utama:

- QR Code untuk anggota dan peminjaman
- Sistem denda otomatis
- Manajemen buku, anggota, peminjaman, pengembalian
- Dashboard admin

## Fitur

- Login & Register
- QR Code generation & scanner
- CRUD Buku dan Anggota
- Peminjaman & Pengembalian
- Penghitungan denda

## Prasyarat

- PHP 8.1+, Composer, MySQL, ekstensi PHP: intl, gd

## Cara Instal (Singkat)

1. Clone repository: `git clone https://github.com/Draconik513/si-perpustakaan-qr-kelompok9.git`
2. Masuk ke folder project: `cd sistem-perpustakaan-qr-code`
3. Install dependencies: `composer install`
4. Salin file environment: `cp .env.example .env` -> sesuaikan DB
5. Buat database baru: `db_book_library`
6. Jalankan migrasi tabel: `php spark migrate --all`
7. Buat akun SuperAdmin: `php spark db:seed SuperAdminSeeder`
8. Jalankan aplikasi: `php spark serve` 

Buka di browser:  
**http://localhost:8080**


## Akun Demo

- admin: superadmin@admin.com / superadmin

## Cara Push ke GitHub
git add .
git commit -m "Add Sistem Informasi Perpustakaan QR Code"
git push -u origin main

## Catatan
- Jangan commit file `.env`
- Jika ingin menggunakan data dummy, jalankan:
