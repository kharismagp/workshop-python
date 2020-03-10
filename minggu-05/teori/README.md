# Minggu-03

> Input and Output<br>
> Bab 7

## 7.1. Fancier Output Formatting
1. Untuk menggunakan Formatted string literals, mulai string dengan f atau F sebelum quotation mark atau triple quotation mark.
2. Metode `str.format()` dari string membutuhkan lebih banyak upaya manual. Anda masih akan menggunakan `{`dan`}` untuk menandai di mana variabel akan diganti dan dapat memberikan arahan pemformatan terperinci, tetapi Anda juga harus memberikan informasi yang akan diformat.

### 7.1.1 Formatted String Literals 
Formatted String Literals (juga singkatnya f-strings) memungkinkan Anda memasukkan nilai ekspresi Python di dalam string dengan mengawali string dengan f atau F dan menulis ekspresi sebagai {ekspresi}.

### 7.1.2. The String format() method
Tanda kurung dan karakter di dalamnya (disebut format field) diganti dengan objek yang diteruskan ke metode str.format (). Angka dalam kurung dapat digunakan untuk merujuk ke posisi objek yang dilewatkan ke metode `str.format()`.

### 7.1.3. Manual String Formatting
Metode `str.rjust()` dari objek string benar-membenarkan string dalam bidang dengan lebar tertentu dengan menambahkannya dengan spasi di sebelah kiri. Ada metode serupa `str.ljust()` dan `str.center()`. Metode ini tidak menulis apa pun, mereka hanya mengembalikan string baru. Jika string input terlalu panjang, mereka tidak memotongnya, tetapi mengembalikannya tidak berubah; ini akan mengacaukan tata letak kolom Anda tetapi itu biasanya lebih baik daripada alternatif, yang akan berbohong tentang suatu nilai. (Jika Anda benar-benar menginginkan pemotongan, Anda selalu dapat menambahkan operasi slice, seperti pada `x.ljust (n) [: n]`.)

### 7.1.4 Old string formatting
Operator `%` juga dapat digunakan untuk pemformatan string. Ini mengartikan argumen kiri seperti string format gaya `sprintf()` untuk diterapkan pada argumen yang benar, dan mengembalikan string yang dihasilkan dari operasi pemformatan ini