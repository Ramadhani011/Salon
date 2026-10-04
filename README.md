# 💇 Resana Salon
Resana Salon merupakan aplikasi berbasis web yang dibuat untuk membantu proses pemesanan dan pengelolaan layanan salon. 
Aplikasi ini menyediakan halaman booking untuk pelanggan serta halaman admin untuk memantau dan mengelola data salon.

## 🌐 Demo

**Website:**  
https://salon2-production.up.railway.app/pelanggan

Aplikasi dijalankan secara online menggunakan Railway dan Docker.

## 📌 Yang Bisa Dilakukan

### Untuk Pelanggan
- Mengisi data pelanggan
- Memilih model haircut
- Menentukan jadwal kunjungan
- Menentukan jumlah orang
- Memilih metode pembayaran
- Melakukan booking salon
- Melihat data booking

### Untuk Admin
- Login ke sistem
- Melihat ringkasan data salon
- Mengelola data pelanggan
- Mengelola data booking
- Menambah dan mengatur layanan
- Melihat data pembayaran
- Membatalkan atau menghapus booking

## ⚙️ Teknologi yang Digunakan

- **Java 17**
- **Spring Boot 3.3.5**
- **Thymeleaf**
- **Spring Data JPA / Hibernate**
- **PostgreSQL**
- **Maven**
- **Docker**
- **Railway**
- **Supabase**

## ▶️ Menjalankan Project

Clone repository terlebih dahulu:

```bash
git clone https://github.com/Ramadhani011/Salon.git
cd Salon
```

Kemudian pastikan konfigurasi database sudah tersedia pada
application.properties.

Jalankan aplikasi dengan Maven:

Windows

```bash
mvnw.cmd spring-boot:run
```

Linux / macOS

```bash
./mvnw spring-boot:run
```

Setelah berhasil dijalankan, buka:

```
http://localhost:8081/pelanggan
```

## 🗂️ Struktur Sistem

Aplikasi terdiri dari beberapa bagian utama:

Customer — proses pendaftaran dan booking
Booking — pengaturan jadwal dan layanan
Payment — pencatatan pembayaran
Admin — pengelolaan data salon
