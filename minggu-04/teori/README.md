# Minggu-04

> Modules<br>
> Bab 6

## 6. Modules
Jika Anda keluar dari interpreter Python dan memasukkannya lagi, definisi yang Anda buat (fungsi dan variabel) akan hilang. Oleh karena itu, jika Anda ingin menulis program yang agak lebih lama, Anda lebih baik menggunakan editor teks untuk menyiapkan input bagi penerjemah dan menjalankannya dengan file itu sebagai input. Ini dikenal sebagai membuat skrip . Saat program Anda menjadi lebih lama, Anda mungkin ingin membaginya menjadi beberapa file untuk memudahkan perawatan. Anda mungkin juga ingin menggunakan fungsi praktis yang Anda tulis di beberapa program tanpa menyalin definisi ke setiap program.

### 6.1. More on Modules
Modul dapat berisi pernyataan yang dapat dieksekusi serta definisi fungsi. Pernyataan-pernyataan ini dimaksudkan untuk menginisialisasi modul. Mereka dieksekusi hanya pertama kali nama modul ditemui dalam pernyataan impor. 1 (Mereka juga dijalankan jika file dieksekusi sebagai skrip.)

### 6.1.2. The Module Search Path
Ketika sebuah modul bernama spamdiimpor, penerjemah pertama mencari modul bawaan dengan nama itu. Jika tidak ditemukan, ia kemudian mencari file bernama spam.pydalam daftar direktori yang diberikan oleh variabel sys.path. sys.pathdiinisialisasi dari lokasi ini:

- Direktori yang berisi skrip input (atau direktori saat ini ketika tidak ada file ditentukan).
- PYTHONPATH (daftar nama direktori, dengan sintaksis yang sama dengan variabel shell PATH).
- Default yang bergantung pada instalasi.

## 6.2. Standard Modules
Python dilengkapi dengan pustaka modul standar, yang dijelaskan dalam dokumen terpisah, Referensi Pustaka Python (“Pustaka Referensi” selanjutnya). Beberapa modul dibangun ke interpreter; ini menyediakan akses ke operasi yang bukan bagian dari inti bahasa tetapi tetap dibangun, baik untuk efisiensi atau untuk menyediakan akses ke sistem operasi primitif seperti panggilan sistem. Set modul tersebut adalah opsi konfigurasi yang juga tergantung pada platform yang mendasarinya.

## 6.4. Packages
Paket adalah cara penataan namespace modul Python dengan menggunakan "dotted module names". Sebagai contoh, nama modul A.Bmenunjuk sebuah submodule bernama Bdalam sebuah paket bernama A. Sama seperti penggunaan modul menyelamatkan penulis modul yang berbeda dari harus khawatir tentang nama variabel global masing-masing, penggunaan nama modul bertitik menyimpan penulis paket multi-modul seperti NumPy atau Bantal dari harus khawatir tentang nama modul masing-masing .