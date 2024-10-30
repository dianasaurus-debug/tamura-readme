# Otodeli Website 
### Ringkasan project
| Nama         | Nilai               |
|--------------|---------------------|
| Tech Stack     | Laravel, CSS, JS, HTML, Bootstrap, JQuery |
| Tipe         | API & Admin Page     |
| Endpoint API         | /api        |

### Integrated 3rd API

- Firebase
- Google Map API
- Whatsapp
- E-Mail
- Tokopedia API

### Required environments

- Apache Web Server
- MySQL Database Server
- PHP 8.0
- Composer

### Required Tools
- Code Editor (VSCode, PHPStorm, Sublime etc)
- Web Browser
- Command Line
- API Tester (Postman, Insomnia, dll)

## Intro

Selamat datang di dokumentasi Website Otodeli, Project Website ini berguna untuk
- REST API untuk aplikasi Otodeli.id untuk order, visit store, aplikasi kehadiran, dll
- Mengelola data produk, order, store, tagihan, retur, dll
- Melihat Report order, stock, retur dll
- Melihat daftar hadir karyawan

## Requirements dan Environments

Dalam pengembangan, semua dilakukan di local server (XAMPP, LAMPP, dll) yang dapat menyediakan service Web Server, Database MySQL server dan PHP.
Disini kami menggunakan PHP 8.0 dan anda tetap membutuhkan composer di local anda untuk menginstall packages yang ada di project.


## Start-Up

1. Silahkan clone project ini di https://gitlab.com/k3066/otodeli-web.git.
2. Setelah masuk jalankan `composer install`.
3. Setelah selesai silahkan buat berkas `.env`  dan isikan isi dari file .env.example. Lalu pastikan semua atribut pada `.env` sudah diarahkan dengan benar ke setiap alat pengembangan yang andai pakai di komputer Anda.
5. Jalankan perintah `php artisan storage:link` untuk membuat asset yang ada di storage bisa diakses oleh website.
6. Jalankan perintah `php artisan migrate --seed` untuk menjalankan migration dan seeder. Akun default adalah `superadmin@otodeli.id` dengan password `password`.
7. Untuk mengakses website, jalankan `php artisan serve` lalu Anda dapat mengakses halaman web melalui `http://localhost:8000`
8. Selamat mengeksplorasi :)
