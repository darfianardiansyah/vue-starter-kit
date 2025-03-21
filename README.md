# Laravel Vue Starterkit - Proyek Belajar

Proyek ini dibuat sebagai bahan belajar dalam mengembangkan aplikasi dengan **Laravel** sebagai backend dan **Vue.js** sebagai frontend.

## 📌 Fitur

- Autentikasi bawaan Laravel Breeze/Inertia
- Vue.js sebagai frontend dengan Vite
- API backend dengan Laravel
- Komponen Vue siap pakai

## 🚀 Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/darfianardiansyah/vue-starter-kit.git
cd vue-starter-kit
```

### 2. Install Dependensi

```bash
composer install
npm install
```

### 3. Konfigurasi Environment

```bash
cp .env.example .env
php artisan key:generate
```

Atur koneksi database di `.env`:

```ini
DB_DATABASE=laravel_vue
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Migrasi Database

```bash
php artisan migrate
```

### 5. Jalankan Aplikasi

```bash
php artisan serve
npm run dev
```

Buka **http://127.0.0.1:8000** di browser.

## 📂 Struktur Folder Utama

```
├── app/          # Backend Laravel
├── resources/
│   ├── js/      # Vue.js frontend
│   ├── views/   # Blade templates
├── routes/
│   ├── web.php  # Routing frontend
│   ├── api.php  # API endpoints
```

## 🛠️ Build untuk Production

```bash
npm run build
```

## 💡 Tujuan Pembelajaran

- Memahami integrasi Laravel dengan Vue.js
- Mempelajari konsep API dengan Laravel
- Menggunakan Vite untuk asset bundling
- Implementasi autentikasi dengan Laravel Breeze

---

Proyek ini dibuat untuk keperluan belajar dan eksplorasi teknologi Laravel & Vue. 🚀
