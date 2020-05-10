#### Nama : Kharisma Gilang P
#### NIM : 175410127
---
### Minggu-09
> Bab 12 dan [dokumentasi Conda](https://conda.io/projects/conda/en/latest/user-guide/index.html).

## Getting started with conda

Sebelum memulai komputer anda harus lebih dulu terinstall [Anaconda](https://docs.anaconda.com/anaconda/install/)

### Memulai Conda

#### Windows
- Dari Start menu cari dan buka Anaconda Prompt
![anaconda prompt](https://docs.conda.io/projects/conda/en/latest/_images/anaconda-prompt.png)

### Mengelola conda

Verifikasi bahwa conda diinstal dan berjalan di komputer anda dengan mengetik:

`conda --version`

Perbarui conda ke versi saat ini. Ketikkan yang berikut ini:

`conda update conda`

Conda membandingkan versi dan kemudian menampilkan apa yang tersedia untuk diinstal.

Jika versi terbaru dari conda tersedia, ketik y untuk memperbarui:

`Proceed ([y]/n)? y`

### Mengelola environtments

Conda memungkinkan Anda untuk membuat lingkungan terpisah yang berisi file, paket, dan dependensinya yang tidak akan berinteraksi dengan lingkungan lain.

Ketika Anda mulai menggunakan conda, Anda sudah memiliki default environment bernama `base`. Buat lingkungan terpisah untuk menjaga program Anda terisolasi satu sama lain.

1. Buat lingkungan baru dan instal paket di dalamnya.

   Kita beri nama environment `snowflakes` dan instal paket BioPython. Di Anaconda Prompt atau di jendela terminal Anda, ketikkan yang berikut:
   
   `conda create --name snowflakes biopython`
   
   Conda memeriksa untuk melihat paket tambahan apa ("dependencies") yang diperlukan BioPython, dan menanyakan apakah Anda ingin melanjutkan:
   
   `Proceed ([y]/n)? y`
   
   Ketik "y" dan tekan Enter untuk melanjutkan.
   
2. Untuk menggunakan, atau "mengaktifkan" environment baru, ketikkan yang berikut:

   - Windows: `conda activate snowflakes`
   
   Untuk versi conda sebelum 4.6, ketik:
   
   - Windows: `activate snowflakes`
   
   Sekarang Anda berada di environment `snowflakes`, perintah conda apa pun yang anda ketikkan akan masuk ke environment itu hingga anda menonaktifkannya.
   
3. Untuk melihat daftar semua lingkungan Anda, ketik:

   `conda info --envs`
   
   Daftar environment muncul, mirip dengan yang berikut:
   ```
   conda environments:

    base           /home/username/Anaconda3
    snowflakes   * /home/username/Anaconda3/envs/snowflakes
    ```
    
    
4. Ubah environment anda saat ini kembali ke default(base): `conda activate`

### Mengelola Python

Saat Anda membuat environment baru, Anda dapat menginstal versi Python yang sama dengan yang Anda gunakan saat mengunduh dan menginstal Anaconda.

1. Membuat environment baru yang bernama "snakes" yang berisi Python 3.5:

   `conda create --name snakes python=3.5`
   
   Ketika conda menanyakan apakah Anda ingin melanjutkan, ketik "y" dan tekan Enter.
   
2. Aktifkan environment baru:

   - Windows: `conda activate snakes`
   
   
3. Verifikasi bahwa environment snakes telah ditambahkan dan aktif:

   `conda info --envs`
   
   Conda menampilkan daftar semua environment dengan tanda bintang (*) setelah nama lingkungan aktif:
   
   
```
# conda environments:
#
base                     /home/username/anaconda3
snakes                *  /home/username/anaconda3/envs/snakes
snowflakes               /home/username/anaconda3/envs/snowflakes
```

     Environment aktif juga ditampilkan di depan prompt Anda di `(tanda kurung)` atau `[tanda kurung]` seperti ini:
    
    `(snakes) $ `
   
   
4. Verifikasi versi Python mana di lingkungan Anda saat ini:

   `python --version`
   
   
5. Deaktifasi environment snakes dan kembali ke base environment: `conda activate`


### Mengelola paket

Di bagian ini, Anda memeriksa paket mana yang telah Anda instal, memeriksa paket mana yang tersedia dan mencari paket tertentu dan menginstalnya.

1. Untuk menemukan paket yang telah Anda instal, pertama-tama aktifkan lingkungan yang ingin Anda cari. Lihat di atas untuk perintah untuk mengaktifkan environment anda.


2. Periksa untuk melihat apakah paket yang belum Anda instal bernama "beautifulsoup4" tersedia dari repositori Anaconda (harus terhubung ke Internet):

   `conda search beautifulsoup4`
   
   Conda menampilkan daftar semua paket dengan nama itu di repositori Anaconda, jadi tahu itu tersedia.
   
   
3. Insatl paket ini ke envoronment saat ini:

   `conda install beautifulsoup4`
   
   
4. Periksa untuk melihat apakah program yang baru diinstal di lingkungan ini:

   `conda list`