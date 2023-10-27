## Program Tagihan SPP Sekolah v1.0
Aplikasi untuk memaintain Tagihan Pembayaran Sekolah Berbasis Web Admin dengan Memanfaatkan Teknologi Laravel v9.x

### How to run it?
Untuk menjalankan program dari repository ini berikut tahapannya

```
composer update
composer install
```

Lalu kemudian ketikkan command dibawah ini untuk generate key application wajib dilakukan

```
php artisan key:generate
```

Kemudian copy file `.env.example` lalu ubah namanya menjadi `.env`, Jika sudah kemudian jalankan command 

```
php artisan serve
```

Dan klik tautan, Boom! Ready for dev bruh...