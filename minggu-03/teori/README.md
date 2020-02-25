# Minggu-03

> Struktur Data<br>
> Bab 5

- ## Function on Lists
    - `list.append(x)`
    - `list.extend(iterable)`
    - `list.insert(i, x)`
    - `list.remove(x)`
    - `list.pop([i])`
    - `list.clear()`
    - `list.index(x[,start[, end]])`
    - `list.count(x)`
    - `list.sort(key=None, reverse=False)`
    - `list.reverse()`
    - `list.copy()`

- ## 5.1.1. Using Lists as Stacks

Metode list membuatnya sangat mudah untuk menggunakan list sebagai stack, di mana elemen terakhir yang ditambahkan adalah elemen pertama yang diambil ("last-in, first-out"). Untuk menambahkan item ke bagian atas tumpukan, gunakan append (). Untuk mengambil item dari atas tumpukan, gunakan pop () tanpa indeks eksplisit

- ## 5.1.2. Using Lists as Queues

Dimungkinkan juga untuk menggunakan lists sebagai queues, di mana elemen pertama yang ditambahkan adalah elemen pertama yang diambil ("masuk pertama, keluar pertama"); namun, daftar tidak efisien untuk tujuan ini. Sementara menambahkan dan muncul dari akhir daftar cepat, melakukan memasukkan atau muncul dari awal daftar lambat (karena semua elemen lain harus digeser oleh satu).

- ## 5.1.3. List Comprehensions

List comprehensions menyediakan cara singkat untuk membuat daftar. Aplikasi umum adalah membuat daftar baru di mana setiap elemen adalah hasil dari beberapa operasi yang diterapkan pada setiap anggota dari urutan lain atau dapat diubah, atau untuk membuat urutan elemen-elemen yang memenuhi kondisi tertentu.

- ## 5.1.4. Nested List Comprehensions

Ekspresi awal dalam pemahaman daftar dapat berupa ekspresi sembarang, termasuk list comprehension lainnya.

- ## 5.2. The `del` statement

Ada cara untuk menghapus item dari daftar yang diberikan indeksnya, bukan nilainya: pernyataan del. Ini berbeda dari metode pop () yang mengembalikan nilai. Pernyataan del juga dapat digunakan untuk menghapus irisan dari daftar atau menghapus seluruh daftar (yang kami lakukan sebelumnya dengan menetapkan daftar kosong ke slice)

- ## 5.3. Tuples and sequences
Kami melihat bahwa daftar dan string memiliki banyak properti umum, seperti operasi pengindeksan dan pemotongan. Mereka adalah dua contoh tipe data urutan (lihat Jenis Urutan - daftar, tupel, kisaran). Karena Python adalah bahasa yang berkembang, tipe data urutan lainnya dapat ditambahkan. Ada juga tipe data urutan standar lain: tuple.

- ## 5.4. Sets
Python juga menyertakan tipe data untuk set. Set adalah koleksi yang tidak diurut tanpa elemen duplikat. Penggunaan dasar meliputi pengujian keanggotaan dan menghilangkan entri duplikat. Atur objek juga mendukung operasi matematika seperti penyatuan, persimpangan, perbedaan, dan perbedaan simetris.

- ## 5.5. Dictionaries
Kamus kadang-kadang ditemukan dalam bahasa lain sebagai "memori asosiatif" atau "array asosiatif". Tidak seperti urutan, yang diindeks oleh sejumlah angka, kamus diindeks oleh kunci, yang bisa berupa tipe apa pun yang tidak berubah; string dan angka selalu bisa menjadi kunci. Tuples dapat digunakan sebagai kunci jika hanya berisi string, angka, atau tupel; jika sebuah tuple berisi objek yang bisa berubah baik secara langsung atau tidak langsung, itu tidak dapat digunakan sebagai kunci. Anda tidak dapat menggunakan daftar sebagai kunci, karena daftar dapat dimodifikasi di tempat menggunakan penugasan indeks, penugasan slice, atau metode seperti menambahkan () dan memperluas ().

- ## 5.6. Looping Techniques
Saat perulangan melalui kamus, kunci dan nilai terkait dapat diambil pada saat yang sama menggunakan metode items ().


