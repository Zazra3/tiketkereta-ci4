# Sistem Ticketing Kereta Api

Aplikasi pemesanan tiket kereta api berbasis web yang dikembangkan menggunakan PHP, CodeIgniter 4, dan MySQL. Sistem ini memungkinkan pengguna mencari jadwal kereta, memilih kursi, melakukan pemesanan, dan mengelola data booking secara mudah.

## Fitur Utama

- Login dan Registrasi Pengguna
- Pencarian Jadwal Kereta
- Filter dan Sorting Kereta
- Pemilihan Kursi
- Booking Tiket Kereta
- Simulasi Pembayaran
- Riwayat Pemesanan
- Dashboard Pengguna

## 🛠️ Teknologi yang Digunakan

- PHP
- CodeIgniter 4
- MySQL
- HTML5
- CSS3
- Bootstrap
- JavaScript

## Struktur Sistem

### Authentication
- Login
- Register
- Logout

### Booking
- Cari Kereta
- Pilih Kereta
- Isi Data Penumpang
- Pilih Kursi
- Pembayaran
- Konfirmasi Booking

## Database

Database digunakan untuk menyimpan:

- Data pengguna
- Data kereta
- Data kursi
- Data booking
- Data transaksi

## Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/username/sistem-ticketing-kereta.git
```

### 2. Masuk ke Folder Project

```bash
cd sistem-ticketing-kereta
```

### 3. Install Dependency

```bash
composer install
```

### 4. Konfigurasi Database

Edit file:

```env
.env
```

Sesuaikan:

```env
database.default.hostname = localhost
database.default.database = tiket_kereta
database.default.username = root
database.default.password =
database.default.DBDriver = MySQLi
```

### 5. Jalankan Server

```bash
php spark serve
```

Akses melalui:

```
http://localhost:8080
```

## 📸 Tampilan Sistem

Tambahkan screenshot aplikasi pada bagian ini.

### Halaman Login
![Login](images/login.png)

### Pencarian Kereta
![Search](images/search.png)

### Pemilihan Kursi
![Seat](images/kursi.png)

### Booking Tiket
![Booking](images/booking.png)

## Developer

**Azzahra Putri**

- GitHub: https://github.com/Zazra3
- Email: azzahraputri0310@gmail.com

## 📄 License

Project ini dibuat untuk kebutuhan pembelajaran dan pengembangan portofolio.
