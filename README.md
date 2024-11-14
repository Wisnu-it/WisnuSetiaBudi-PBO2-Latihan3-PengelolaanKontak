# WisnuSetiaBudi-PBO2-Latihan3-PengelolaanKontak
# Aplikasi Pengelolaan Kontak

Aplikasi **Pengelolaan Kontak** adalah program berbasis Java Swing yang memungkinkan pengguna untuk mengelola daftar kontak. Fitur yang tersedia meliputi menambah, mengedit, menghapus, mencari, mengimpor, dan mengekspor data kontak.

## Fitur Utama
- **Tambah Kontak**: Menambahkan kontak baru ke dalam daftar.
- **Edit Kontak**: Memperbarui informasi kontak yang sudah ada.
- **Hapus Kontak**: Menghapus kontak yang dipilih dari daftar.
- **Pencarian Kontak**: Mencari kontak berdasarkan nama atau nomor telepon.
- **Ekspor Data**: Mengekspor daftar kontak ke dalam file CSV.
- **Impor Data**: Mengimpor data kontak dari file CSV.

## Teknologi yang Digunakan
- **Java**: Bahasa pemrograman utama.
- **Swing**: Library GUI untuk membuat antarmuka pengguna.
- **JDBC**: Untuk koneksi ke database.
- **CSV**: Format file untuk ekspor dan impor data.

## Prasyarat
Sebelum menjalankan aplikasi ini, pastikan:
- **Java JDK 8 atau versi yang lebih baru** telah terpasang di sistem Anda.
- **Database** yang mendukung JDBC. Sebagai contoh, Anda dapat menggunakan MySQL atau SQLite.
- Aplikasi **NetBeans IDE** (opsional), untuk pengembangan dan pengujian lebih lanjut.

## Instalasi dan Konfigurasi
1. **Kloning repositori**:
   ```bash
   git clone https://github.com/username/pengelolaan-kontak.git
   cd pengelolaan-kontak

    Konfigurasi Database:
        Buat database baru (misalnya kontak_db) dan tabel yang diperlukan untuk menyimpan data kontak.
        Sesuaikan konfigurasi database di dalam kode pada bagian dbHelper (seperti URL, username, dan password untuk koneksi database).

    Kompilasi dan Jalankan:
        Gunakan NetBeans atau IDE favorit Anda untuk membuka proyek dan menjalankan aplikasi.
        Anda juga dapat menggunakan command line untuk kompilasi:

        javac PengelolaanKontakFrame.java
        java PengelolaanKontakFrame

Penggunaan

    Menambah Kontak: Isi nama, nomor, dan kategori kontak, lalu klik tombol "Tambah".
    Edit Kontak: Pilih kontak dari tabel, perbarui data di kolom input, dan klik tombol "Edit".
    Hapus Kontak: Pilih kontak dari tabel dan klik tombol "Hapus".
    Cari Kontak: Masukkan kata kunci di kolom pencarian, klik tombol "Cari".
    Ekspor/Impor Kontak: Gunakan tombol "Ekspor" untuk menyimpan data dalam CSV atau "Impor" untuk memuat data dari CSV.

Struktur Proyek

    PengelolaanKontakFrame.java: File utama berisi antarmuka pengguna dan event handling.
    dbHelper.java: Class untuk mengelola koneksi dan operasi database.
    resources/: Folder berisi file CSV untuk ekspor dan impor (jika diperlukan).

![image](https://github.com/user-attachments/assets/2d8ecfbd-e5e7-4568-9bc3-6a83d27c50d8)
