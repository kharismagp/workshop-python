# Minggu-06

> Errors and Exceptions<br>
> Bab 8

## Errors and Exceptions
Sampai sekarang pesan kesalahan belum lebih dari yang disebutkan, tetapi jika Anda telah mencoba contohnya, Anda mungkin telah melihat beberapa. Ada (setidaknya) dua jenis kesalahan yang dapat dibedakan: kesalahan sintaksis dan pengecualian .

## 8.1. Syntax Errors
Kesalahan sintaksis, juga dikenal sebagai kesalahan parsing, mungkin jenis keluhan paling umum yang Anda dapatkan saat Anda masih belajar Python:

## 8.2. Exceptions
Bahkan jika suatu pernyataan atau ungkapan secara sintaksis benar, itu dapat menyebabkan kesalahan ketika suatu usaha dilakukan untuk mengeksekusinya. Kesalahan yang terdeteksi selama eksekusi disebut pengecualian dan tidak berakibat fatal

## 8.3. Handling Exceptions
Dimungkinkan untuk menulis program yang menangani pengecualian yang dipilih. Lihatlah contoh berikut ini, yang meminta input dari pengguna sampai integer yang valid telah dimasukkan, tetapi memungkinkan pengguna untuk menginterupsi program (menggunakan Control-Catau apa pun yang didukung sistem operasi)

## 8.4. Raising Exceptions
Pernyataan `raise` memungkinkan programmer untuk memaksa pengecualian tertentu terjadi.

## 8.5. User-defined Exceptions
Program dapat memberi nama pengecualian mereka sendiri dengan membuat kelas pengecualian baru . Pengecualian biasanya berasal dari `Exception` kelas, baik secara langsung maupun tidak langsung. 

## 8.6. Defining Clean-up Actions
pernyataan `try` memiliki klausul opsional lain yang dimaksudkan untuk menentukan tindakan bersih-bersih yang harus dijalankan dalam semua keadaan.

## 8.7. Predefined Clean-up Actions
Beberapa objek mendefinisikan tindakan pembersihan standar yang harus dilakukan ketika objek tidak lagi diperlukan, terlepas dari apakah operasi menggunakan objek berhasil atau gagal.