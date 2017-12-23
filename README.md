# laravelreactnative


Aplikasi ini menggunakan Laravel 5.5, api nya dapat digunakan untuk mobile development


Minimum Requirements
PHP versi 7 atau diatasnya
Composer Package Manager
NodeJS dan NPM
Gulp

Cara menjalankan aplikasi
Clone project ini

https://github.com/fauzanlbs/laravelreactnative.git
Install package dependency vendor untuk laravel

composer install
Install dependency modul tambahan

npm install
Konfigurasi database

Buat file .env di dalam root directory
Copy isi dari file .env.example lalu paste di dalam file .env
Isi informasi database : DB_DATABASE, DB_USERNAME dan DB_PASSWORD
Jalankan perintah dibawah untuk menghasilkan key

php artisan key:generate
Jalankan perintah dibawah ini untuk membuat tabel-tabel dan seeding datanya

php artisan migrate:refresh --seed
Jalankan perintah ini untuk membuild plugin tambahan

gulp
Setup domain di homestead atau buat virtualhost di server atau jalankan built in server bawaan laravel dengan perintah

php artisan serve
