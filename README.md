# install-laragon-laravel

# Dokumentasi Instalasi Laragon dan Laravel

Repositori ini berisi panduan lengkap untuk mengunduh dan menginstal Laragon serta Laravel di sistem operasi Windows. Dokumen ini juga mencakup langkah-langkah menjalankan Laravel melalui Laragon.

## 1. Persiapan

Sebelum memulai, pastikan koneksi internet aktif dan stabil karena proses instalasi Laravel membutuhkan akses untuk mengunduh dependensi melalui Composer.

## 2. Download Laragon

1. Buka browser dan kunjungi situs resmi Laragon: https://laragon.org
2. Klik tombol "Download"
3. Pilih versi **Laragon Full** agar langsung tersedia PHP, Apache/Nginx, MySQL, Composer, dan Node.js
4. Setelah file instalasi selesai diunduh (biasanya berekstensi `.exe`), lanjut ke tahap instalasi

## 3. Instalasi Laragon

1. Jalankan file `Laragon.exe` sebagai Administrator
2. Pilih lokasi instalasi, misalnya `C:\laragon`
3. Klik "Next" hingga proses instalasi selesai
4. Jalankan Laragon, lalu klik tombol "Start All" untuk mengaktifkan semua layanan
5. Jika browser terbuka dan menampilkan halaman `localhost`, maka Laragon berhasil dijalankan

## 4. Instalasi Laravel

Laravel dapat di-instal langsung melalui terminal bawaan Laragon menggunakan Composer.

### Langkah-langkah:

1. Buka **Terminal Laragon** melalui menu Laragon:
   - Klik "Menu" > "Terminal"

2. Arahkan ke direktori `www` tempat project Laravel akan dibuat:
   ```bash
   cd C:\laragon\www
