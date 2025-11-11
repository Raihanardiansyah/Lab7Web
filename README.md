# Pratikum 7 - PHP Dasar
### NAMA : Raihan Ardiansyah
### NIM : 312410396
### KELAS : TI.24.A3

## 📍LANGKAH - LANGKAH PENGERJAAN

### 1. Persiapan 

Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP
terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7.
Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu
XAMPP.

**Install XAMPP**

Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi
portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan
direktorinya (misal: d:\xampp).

<img src="xampp1.png" width="700">

Konfigurasi Web Server

• Konfigurasi Apache

Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul
yang diaktifkan, lokasi document root, dll.

Lokasi file: \xampp\apache\conf\httpd.conf

• Konfigrasi PHP

Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.
Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload, error
reporting, dll.

Lokasi file: \xampp\php\php.ini

• Konfigrasi MySql

Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.

Lokasi file: \xampp\mysql\bin\my.ini

**Menjalankan Web Server**

Untuk menjalankan web server dari menu XAMPP Control.

<img src="xampp2.png" width="700">

• Uji coba apakah server sudah berkerja dengan baik

http://127.0.0.1 atau http://localhost

Tampil halaman utama XAMPP jika server sudah berkerja dengan baik.

• Dokumen Website

Semua file website tempatkan di direktori: \xampp\htdocs\

• Database MySQL

Direktori: \xampp\mysql\

Manajemen database: http://localhost/phpmyadmin

**Memulai PHP**

Buat folder lab7_php_dasar pada root directory web server (d:\xampp\htdocs)

<img src="xampp3.png" width="700">

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:

http://localhost/lab7_php_dasar/

<img src="xampp4.png" width="700">

**PHP Dasar**

Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut.

<img src="code1.png" width="700">

Kemudian untuk mengakses hasilnya melalui URL:

http://localhost/lab7_php_dasar/php_dasar.php

<img src="gambar1.png" width="700">

**Variable PHP**

Menambahkan variable pada program.

<img src="code2.png" width="700">

<img src="gambar2.png" width="700">

**Predefine Variable $_GET**

<img src="code3.png" width="700">

Untuk mengaksesnya gunakan URL:

http://localhost/lab7_php_dasar/latihan2.php?nama=Agung

<img src="gambar3.png" width="700">

Membuat Form Input

<img src="code4.png" width="700">

<img src="gambar4.png" width="700">

**Operator**

<img src="code5.png" width="700">

**Kondisi IF**

<img src="code6.png" width="700">

**Kondisi Switch**

<img src="code7.png" width="700">

**Perulangan for**

<img src="code8.png" width="700">

**Perulangan while**

<img src="code9.png" width="700">

**Perulangan dowhile**

<img src="code10.png" width="700">

**Pertanyaan dan Tugas**

Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan
nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung
umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang
berbeda-beda sesuai pilihan pekerjaan.

<img src="code11.png" width="700">

<img src="gambar5.png" width="700">
