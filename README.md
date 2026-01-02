# Sistem Manajemen Kasus Digital - Dit Reskrim Umum (Polda Sultra)

![Status](https://img.shields.io/badge/Status-Production-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-High-red?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)

> **⚠️ NOTE:** Repository ini adalah **Distribution Channel**. Source code aplikasi bersifat **Private (Proprietary)** karena memuat logika keamanan data sensitif instansi kepolisian.

---

## 🛡️ Tentang Aplikasi
**Sistem Manajemen Kasus (Case Management System)** ini dikembangkan untuk mendigitalisasi proses penyidikan di lingkungan **Dit Reskrim Umum Polda Sultra**. Aplikasi ini menggantikan pemberkasan manual menjadi sistem terintegrasi yang mampu melacak status kasus, data tersangka, dan barang bukti secara *real-time* dan akurat.

Dibangun dengan arsitektur modern yang mengutamakan **Keamanan Data** dan **Kecepatan Akses**, aplikasi ini mampu menangani ribuan entitas data kasus dengan performa tinggi.

## 💻 Tech Stack (High Performance Engineering)
Aplikasi ini tidak dibangun dengan framework biasa. Kami menggunakan teknologi *systems programming* untuk menjamin stabilitas dan keamanan memori.

### Backend & Core System
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)
* **Rust:** Dipilih karena *Memory Safety* dan kecepatan eksekusi setara C++. Menjamin aplikasi bebas dari bug memori (No Null Pointer Exceptions).
* **Tauri:** Framework desktop masa depan yang menghasilkan ukuran installer sangat kecil (<10MB) dan penggunaan RAM yang sangat efisien dibandingkan Electron.

### Database Management
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
* **PostgreSQL:** Digunakan sebagai tulang punggung penyimpanan data. Dipilih karena fitur *ACID Compliance* yang ketat, kemampuan menangani relasi data kasus yang kompleks (One-to-Many antara Tersangka, Korban, dan Pasal), serta keamanan *Row-Level Security*.

### Frontend Interface
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
* **TypeScript + React:** Menjamin antarmuka yang responsif dengan validasi tipe data yang ketat (Type Safety) untuk meminimalisir error input user.

---

## 🚀 Fitur Utama
1.  **Manajemen Berkas Perkara:** Input data Laporan Polisi (LP) hingga P21.
2.  **Tracking Real-time:** Memantau perkembangan kasus per penyidik.
3.  **Secure Authentication:** Login terenkripsi dengan level akses bertingkat.
4.  **Database Relasional Kuat:** Integrasi data tersangka, barang bukti, dan saksi menggunakan PostgreSQL.
5.  **Report Generator:** Ekspor laporan bulanan otomatis.

## 📥 Cara Download & Instalasi
Aplikasi ini tersedia untuk lingkungan Windows (64-bit).

1.  Buka tab **[Releases](../../releases)** di pojok kanan atas halaman ini.
2.  Pilih versi terbaru (**Latest**).
3.  Klik pada file `.msi` atau `.exe` untuk mengunduh.
4.  Jalankan installer dan ikuti petunjuk instalasi.

---
**Developed by Hilal Hibrizi**
*Focusing on Rust Systems, Secure Architecture, and Scalable Database Solutions.*