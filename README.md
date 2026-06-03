
<h3 align="center">بِسْــــــــــــــمِ اللهِ الرَّحْمَنِ الرَّحِيْــــــــــــــمِ</h3>

---
<br>

### 1. Clone Repository

```bash
git clone https://github.com/Nadyne14/PBL-SistemRekomendasiPekerjaan.git
```

### 2. Masuk ke Direktori Proyek

```bash
cd PBL-SistemRekomendasiPekerjaan
```

### 3. Install Dependensi

```bash
composer install
```

### 4. Konfigurasi File `.env`

```bash
cp .env.example .env
```
- Buat Database baru dengan nama SistemRekomendasiPekerjaan
  di http://localhost/phpmyadmin/index.php
  
- Buka file `.env` dan sesuaikan konfigurasi database:
  ```env
  DB_DATABASE=SistemRekomendasiPekerjaan
  DB_USERNAME=root
  DB_PASSWORD=
  ```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Migrasi Database

```bash
php artisan migrate --seed
```

### 7. Jalankan Server Laravel

```bash
php artisan serve
```

### 8. Akses Aplikasi di Browser

Buka browser dan akses:

```bash
http://127.0.0.1:8000
```
