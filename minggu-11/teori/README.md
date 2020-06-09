#### Nama : Kharisma Gilang P
#### NIM : 175410127
---
### Minggu-11
> Pemrograman Web

## Apa itu Flask?

Flask adalah kerangka kerja aplikasi web WSGI yang ringan . Ini dirancang untuk memulai dengan cepat dan mudah, dengan kemampuan meningkatkan aplikasi yang kompleks. Ini dimulai sebagai pembungkus sederhana di sekitar Werkzeug dan Jinja dan telah menjadi salah satu kerangka kerja aplikasi web Python paling populer.

Flask menawarkan saran, tetapi tidak memberlakukan dependensi atau tata letak proyek. Terserah pengembang untuk memilih alat dan perpustakaan yang ingin mereka gunakan. Ada banyak ekstensi yang disediakan oleh komunitas yang membuat penambahan fungsionalitas baru menjadi mudah.

## Tutorial Flask

### Sebelum memulai pastikan kalian telah menginstall Flask pada environtment yang dituju. Ini link tutorial [install flask](https://flask.palletsprojects.com/en/1.1.x/installation/) nya.

### Ini adalah folder tree hasil akhir dari [tutorial flask](https://flask.palletsprojects.com/en/1.1.x/tutorial/) ini

[![folder-tree.png](https://i.postimg.cc/63cJMsn6/folder-tree.png)](https://postimg.cc/TLK4P4tB)

### Proses pembuatan Table

Database yang digunakan dalam tutorial ini adalah SQLite pada SQLite data disimpan di *tables* dan *columns*. Sebelum kita menyimpan dan membaca data file yang berisi SQL commands ini harus dibuat terlebih dahulu.

Simpan di direktori dan nama flaskr/schema.sql

[![schema-sql.png](https://i.postimg.cc/DwW2FYWw/schema-sql.png)](https://postimg.cc/qNTfxwXP)

### Menambahkan file Python yang dapat menjalankan SQL commands ke db.py

Simpan di direktori dan nama flaskr/db.py

[![commands-function.png](https://i.postimg.cc/jSXdMJJz/commands-function.png)](https://postimg.cc/sMMrXxmX)

### Sebelum project dijalankan pastikan database telah di inisialisasi

[![initialize-database-cmd.png](https://i.postimg.cc/63txV671/initialize-database-cmd.png)](https://postimg.cc/p9GSRHJD)

### Akan ada file dari sqlite yang di generate otomatis setelah inisialisasi di dalam folder instance

[![sqlite.png](https://i.postimg.cc/Gtp0NMxF/sqlite.png)](https://postimg.cc/mzK61yqk)

### Setelah semuanya selesai jalankan projectnya

[![run-flask-app.png](https://i.postimg.cc/Y2XBgHtb/run-flask-app.png)](https://postimg.cc/3WDq5z4v)

### Setelah project dijalankan masuk ke register jika belum membuat akun

[![register-page.png](https://i.postimg.cc/SN30Tf29/register-page.png)](https://postimg.cc/rK1YzW9y)

### Setelah akun dibuat selanjutnya kita bisa melanjutkan ke tahap login

[![login-page.png](https://i.postimg.cc/3NbMHgtP/login-page.png)](https://postimg.cc/tnPv3VQ5)

### Setelah login kita akan mendapat akses untuk membuat postingan di blog tersebut. Saya akan coba membuat satu postingan

[![blog-post.png](https://i.postimg.cc/rpSLtRpr/blog-post.png)](https://postimg.cc/Nyfn3Mms)

### Hasil postingan yang saya posting

[![finish-create.png](https://i.postimg.cc/xTcD34CY/finish-create.png)](https://postimg.cc/N5qzgbmP)

### Melihat record yang tersimpan di database 

Karena database yang digunakan adalah SQLite maka saya memerlukan aplikasi tambahan yaitu [SQLite Browser](https://sqlitebrowser.org/dl/) download dan install aplikasi tersebut.

File berada di direktori instance/schema.sqlite. Klik Open Database dan cari database tersebut.

[![sqlite-browser.png](https://i.postimg.cc/05FncVgq/sqlite-browser.png)](https://postimg.cc/23dn5F8H)

Kemudian, klik tab Browse Data disini ditampilkan data hasil record dari aplikasi blog tutorial ini.

[![data-sqlite.png](https://i.postimg.cc/5276SkGB/data-sqlite.png)](https://postimg.cc/mP9LbVTk)

> **Catatan:** folder venv saya hapus dari project ini agar bisa diupload di github
