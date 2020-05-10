#### Nama : Kharisma Gilang P
#### NIM : 175410127
---
### Minggu-08
> Bab 10 dan 11

## Bried Tour of standard Library

### Operating System Interface
Module os menyediakan banyak fungsi untuk berinteraksi dengan sistem operasi, untuk menggunakanya harus di import dengan "import os"

### File Wildcards
Module glob menyediakan fungsi untuk membuat list file dari pencarian directory wildcard "import glob"

### Command Line arguments
utilitas yang paling umum digunakan adalah menggunakan argument command line. argument ini disimpan di module sys, "import sys"

### Error Output Redirection and Program Termination
module sys juga menyediakan atribut untuk stdin, stdout dan stdeer. ini berguna untuk membuat warning atau error message terlihat ketika stdout ter redirect

### String Pattern Matching
module re menyediakan tool untuk pemrosesan string lebih lanjut "import re"

### Mathematics
moudle math memberi akses di bawah fungsi C library untuk floating point math module random menyediakan tool untuk seleksi acak module statistics menghitung statistika dasar (mean, median, variansi dsb)

### Internet Access
ada beberapa library untuk mengakses internet dan mengatur protokol internet, dua di antaranya adalah urllib.request untuk mengambil data dari url dan smtplib untuk mengirim email

### Dates and Times
module datetime menyediakan kelas untuk memanipulasi tanggal dan waktu secara sederhana atau lebih rumit.

### Data Compression
beberama data archive dan kompresi yang langsung bisa digunakan meliputi : zlib, gzip, bz2, lzma, zipfile dan tarfile

### Performance Measurement
module timeit menyediakan mengukur kecepatan suatu kode di eksekusi.

### Quality Control
salah satu pendekatan untuk membuat software berkualitas tinggi adalah dengan menulis test untuk setiap fungsi, module doctest menyediakan banyak scanning module dan validating test embeded dalam program