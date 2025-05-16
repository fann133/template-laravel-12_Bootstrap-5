# 👉 Template Laravel^12 pakai Bootstrap^5

Versi Laravel yang digunakan: [Laravel^12](https://laravel.com/docs/12.x)

Template yang digunakan: [Bootstrap^5](https://getbootstrap.com/)

---

## 🎥 Sambil Ngoding Wajib Hukumnya Mendengarkan lagu ini

[![Lihat Video Demo](https://img.youtube.com/vi/CtRIsakAgjQ/0.jpg)](https://youtu.be/CtRIsakAgjQ?si=Durnh1AAhMHUqCLS "Klik untuk menonton di YouTube")

---

## ⚙️ Cara Instalasi

```bash
# 1. Clone project
git clone https://github.com/fann133/template-laravel-12_Bootstrap-5.git

# 2. Masuk ke folder project
cd template-laravel-12_Bootstrap-5

# 3. Install dependencies Laravel
composer install

# 4. Install npm
npm install

# 5. Salin file .env dan sesuaikan konfigurasi database
cp .env.example .env

# 6. Generate app key
php artisan key:generate

# 7. Jalankan npm
npm run dev    //Saat lokal atau ngoding
npm run build //Saat mau upload ke hosting

# 8. Jalankan server lokal
php artisan serve
