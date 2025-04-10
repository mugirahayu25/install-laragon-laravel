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
Berikut adalah **langkah-langkah lengkap** untuk membuat dan menjalankan project Laravel di Laragon, berdasarkan instruksi yang kamu berikan dan disusun agar lebih jelas dan rapi:

## 5. **angkah-langkah Menjalankan Laravel di Laragon**

1. **Buka Terminal Laragon**
   - Buka aplikasi **Laragon**
   - Klik menu **“Menu”** > pilih **“Terminal”**

2. **Arahkan ke direktori `www` Laragon:**
   ```bash
   cd C:\laragon\www

3. **Buat Project Laravel Baru (contoh: `example-app`):**
   ```bash
   composer create-project laravel/laravel example-app
   ---
   > Tunggu proses instalasi selesai. Ini bisa memakan waktu beberapa menit tergantung kecepatan internet.

4. **Masuk ke folder project Laravel (`example-app`):**
   ```bash
   cd example-app

5. **Jalankan Laravel menggunakan perintah artisan:**
   ```bash
   php artisan serve
   
6. **Setelah berhasil, akan muncul tampilan seperti ini:**
   ```
   Starting Laravel development server: http://127.0.0.1:8000

7. **Buka browser**, lalu akses:
   ```
   http://127.0.0.1:8000
   ---
   > Jika berhasil, maka akan tampil halaman welcome dari Laravel (versi 8.0 ke atas tergantung versi yang terinstal).
