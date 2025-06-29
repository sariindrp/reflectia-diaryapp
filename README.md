# 📔 Reflectia – Aplikasi Buku Harian Online Berbasis Mobile  
**Reflectia – Mobile-Based Online Diary App**

Reflectia adalah aplikasi mobile untuk mencatat dan mengelola catatan harian secara digital. Dibuat dengan **Flutter** dan terintegrasi dengan backend **PHP & MySQL** menggunakan REST API.

Reflectia is a mobile app to write and manage daily diary entries digitally. Built using **Flutter** and integrated with a **PHP & MySQL** backend through REST API.

---

## 🎯 Tujuan Aplikasi | App Purpose

- 📝 Pencatatan pribadi praktis dan aman  
  Easy and secure personal journaling  
- 🔐 Menjaga privasi dan keamanan data  
  Ensures data privacy and security  
- 💆‍♀️ Mendukung kesehatan mental  
  Supports mental well-being through journaling  
- 💾 Menyimpan kenangan penting secara digital  
  Safely stores important memories  
- 🌐 Akses dari berbagai perangkat  
  Accessible from various devices

---

## 📱 Fitur Utama | Key Features

- 🧾 Registrasi & login pengguna  
  User registration & login  
- ✍️ Tulis, edit, hapus entri  
  Create, edit, and delete entries  
- 📚 Lihat riwayat catatan  
  View diary history  
- 🔍 Cari entri berdasarkan kata kunci/tanggal  
  Search entries by keyword/date  
- 👤 Ubah data profil pengguna  
  Edit user profile  
- 🔗 Terhubung ke REST API  
  Integrated with REST API

---

## 🛠️ Teknologi yang Digunakan | Tech Stack

### 👨‍💻 Mobile App
- Flutter (Dart)
- HTTP package
- Provider/GetX (opsional)

### 🌐 Backend (API)
- PHP (Native)
- MySQL
- JSON response
- Authentication system

---

## ⚙️ Cara Instalasi Backend | Install Guide (Localhost)

1. Clone atau download repo backend project ini
2. Pindahkan folder project ke dalam folder `htdocs` di XAMPP
3. Buka **phpMyAdmin**, buat database baru (nama bebas)
4. Import file `peers.sql` ke database tersebut
5. Buka file `application/config/database.php`, ubah nama database sesuai dengan yang kamu buat
6. Jalankan project di `http://localhost/namaproject`

> Setelah itu, backend sudah siap diakses oleh aplikasi Flutter!

---

## 🔗 API List (Sementara)

- `GET    /api/user` → Ambil data user saat login  
- `POST   /api/registrasi` → Registrasi user baru  
- `POST   /api/login` → Login user terdaftar  

---

## 📚 Tentang Nama "Reflectia" | About the Name

“Reflectia” berasal dari kata *reflect* yang menggambarkan refleksi diri, dengan akhiran “-ia” untuk kesan elegan.  
“Reflectia” comes from *reflect*, representing self-reflection, with the suffix “-ia” to give a calm and elegant touch.

---

## 🧪 Status Proyek | Project Status

✅ Fungsional / Functional  
⚙️ Terhubung ke Backend / Connected to Backend  
📱 Diuji di Android Emulator / Tested on Android Emulator  
🚧 Pengembangan lanjutan opsional / Optional further development

---

## 🖼️ Cuplikan Tampilan | Screenshots

### 🔐 Halaman Sign In dan Login
![Login](https://github.com/user-attachments/assets/44daab91-5a1d-41da-ade5-278bd5d119ac)
![SignIn](https://github.com/user-attachments/assets/5be103e7-7ad9-4358-85fd-79cea4cd7945)

### 🏠 Beranda / Main Screen
![Home](https://github.com/user-attachments/assets/f896c8ee-01b7-4ba8-9fae-0e18f0ad536d)

### ✍️ Ubah Profile
![Profile](https://github.com/user-attachments/assets/c29ad405-07d7-4460-bdb0-4009c0dcb49d)

---

## 📌 Catatan | Notes

Reflectia dikembangkan sebagai proyek mata kuliah **Pemrograman Mobile** dengan pendekatan fullstack modern (Flutter + REST API).  
Reflectia was developed as a **Mobile Programming** course project using a modern fullstack approach (Flutter + REST API).
