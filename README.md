# Diva Cahya Hakim
## 4523210037

---

# 🧾 Laporan Praktikum: Implementasi Admin Panel dengan Laravel Filament

## 🧠 Deskripsi Proyek
Proyek ini merupakan implementasi **sistem manajemen konten (CMS)** sederhana menggunakan **Laravel** dengan bantuan **Filament Admin Panel**.  
Aplikasi ini digunakan untuk mengelola data **berita**, **wartawan**, dan **komentar** melalui antarmuka admin yang modern dan interaktif.

---

## 🧩 Fitur Utama
1. **Autentikasi Admin**
   - Login menggunakan email dan password.
   - Halaman login disediakan oleh Filament.
   - Proteksi akses ke halaman dashboard hanya untuk pengguna yang sudah login.

2. **Dashboard Admin**
   - Menampilkan ringkasan umum dari sistem.
   - Informasi admin yang sedang login.

3. **Manajemen Wartawan**
   - Menampilkan daftar wartawan.
   - Fitur **Tambah**, **Edit**, dan **Hapus Wartawan**.
   - Setiap wartawan memiliki nama dan email.

4. **Manajemen Berita (News)**
   - Menampilkan daftar berita lengkap dengan wartawan yang menulisnya.
   - Fitur CRUD (**Create, Read, Update, Delete**) berita.
   - Kolom utama: `Nama Wartawan`, `Judul Berita`, `Ringkasan`, dan `Isi`.

5. **Manajemen Komentar**
   - Menampilkan komentar terkait berita.
   - Kolom utama: `Judul Berita`, `Nama Komentator`, `Isi Komentar`.
   - Fitur **Delete Komentar**.

---

## 🧰 Struktur Menu Admin
| Menu | Deskripsi |
|------|------------|
| Dashboard | Menampilkan informasi admin dan versi Filament |
| Komentar | CRUD data komentar berita |
| News | CRUD data berita |
| Wartawans | CRUD data wartawan |

---

## 🖼️ Tampilan Aplikasi

### 1. Halaman Login
Menampilkan form login dengan field **Email Address** dan **Password**.  
<img width="1440" height="900" alt="Tangkapan Layar 2025-11-12 pukul 19 49 59" src="https://github.com/user-attachments/assets/60b2ca78-fd52-40f4-a4ca-ed7418877904" />

---

### 2. Dashboard Admin
Menampilkan halaman utama setelah login berhasil.  
<img width="1440" height="900" alt="Tangkapan Layar 2025-11-12 pukul 19 50 09" src="https://github.com/user-attachments/assets/bd9a988c-ce5b-4744-a376-639ee2a9c55b" />

---

### 3. Halaman Komentar
Daftar komentar yang masuk dari pengguna.  
<img width="1440" height="900" alt="Tangkapan Layar 2025-11-12 pukul 19 50 20" src="https://github.com/user-attachments/assets/9a6a033b-060d-4250-bd0f-2bcd3567b215" />

---

### 4. Halaman Berita
Menampilkan daftar berita yang dibuat oleh wartawan.  
<img width="1440" height="900" alt="Tangkapan Layar 2025-11-12 pukul 19 50 29" src="https://github.com/user-attachments/assets/fbb48065-c64a-4366-b1a2-6f9f8120c82b" />

---

### 5. Halaman Wartawan
Daftar wartawan yang terdaftar di sistem.  
<img width="1440" height="900" alt="Tangkapan Layar 2025-11-12 pukul 19 50 32" src="https://github.com/user-attachments/assets/418f81a4-c565-4c1b-a9fe-d8953120d329" />

---
