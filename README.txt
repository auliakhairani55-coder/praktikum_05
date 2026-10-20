Praktikum Pertemuan 5 - Database Inventori Laboratorium
Nama  :Aprilian Novel Fahlevi
NIM   :25110100
Kelas :tka pagi
Server database : MariaDB/MySQL versi 127.0.0.1
phpMyAdmin      : versi 8.2.12
Nama database   : db_inventori_lab (atau db_inventori_lab_NIM jika nama itu sudah dipakai)

Cara memulihkan database:
1. Jalankan Apache dan MySQL di XAMPP.
2. Buka localhost/phpmyadmin, buat database dengan collation utf8mb4_unicode_ci.
3. Pilih database tersebut > tab Import > pilih skema_inventori_lab.sql > Import.

Isi: 5 tabel (kategori, barang, pengguna, peminjaman, detail_peminjaman), 4 foreign key, 3 check constraint.