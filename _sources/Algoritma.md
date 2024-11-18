---
title: Algoritma

---

# Algoritma

## Definisi
Algoritma pemrograman merupakan ilmu dalam menyusun langkah-langkahyang memiliki struktur untuk membentuk suatu program. Algoritma merupakan fondasi dari semua aktivitas dalam dunia pemrograman. Seorang yang berprofesi sebagai programer dan data analis maupun semacamnya, mereka harus memahami betul mengenai algoritma.

## Algoritm Sequential Search
Algoritma sequential search, juga dikenal sebagai linear search, adalah algoritma pencarian yang memeriksa setiap elemen dalam sebuah kumpulan data secara berurutan untuk menemukan nilai tertentu. Algoritma ini merupakan pendekatan brute-force untuk menemukan nilai target dalam suatu kumpulan. 

- **Cara kerja**
Memeriksa setiap elemen dalam kumpulan data secara berurutan, mulai dari elemen pertama
- **Output**
Jika nilai yang dicari ditemukan, algoritma akan mengembalikan indeksnya. Jika nilai yang dicari tidak ditemukan, algoritma akan mengembalikan -1.
- **Best case**
Algoritma melakukan satu perbandingan dan langsung menemukan nilai yang dicari.
- **Worst case**
Algoritma melakukan n perbandingan dan tidak menemukan nilai yang dicari atau menemukan nilai yang dicari di akhir daftar.

Algoritma sequential search dapat diterapkan pada berbagai aplikasi, seperti aplikasi kamus yang memungkinkan pengguna untuk mencari nama tumbuhan dengan melakukan pencarian secara beruntun.


## Algoritm Binary Search
Binary Search dalah algoritma apencarian cepat dengan kompleksitas waktu proses Ο(log n). Algoritma pencarian ini bekerja berdasarkan prinsip bagi dan taklukkan, karena ia membagi array menjadi dua bagian sebelum melakukan pencarian. Agar algoritma ini bekerja dengan baik, kumpulan data harus dalam bentuk yang terurut.

Binary Search yauitu mencari nilai kunci tertentu dengan membandingkan item paling tengah dari koleksi. Jika terjadi kecocokan, maka indeks item dikembalikan. Namun jika item tengah memiliki nilai lebih besar dari nilai kunci, subarray kanan dari item tengah dicari. Jika tidak, subarray kiri dicari. Proses ini berlanjut secara rekursif hingga ukuran subarray berkurang menjadi nol.


## Pseudocode
pseudocode adalah sebuah cara penulisan program yang informal dan dapat dibuat dengan kaidah yang ditentukan sendiri. Dengan kata lain, pseudocode merupakan urutan logika yang bertujuan untuk dipahami manusia dengan mudah. 

Pseudocode bukanlah bahasa pemrograman, jadi tidak masalah bahasa apa yang Anda gunakan untuk menulis. Umumnya, pseudocode ditulis dengan bahasa Inggris karena lebih mudah ketika mengkonversikannya ke bahasa pemrograman. Tapi juga tidak masalah jika Anda menggunakan bahasa Indonesia. Fungsi utama dari Pseudocode:

- Sebagai media dokumentasi
- Sebagai titik tengah antara flowchart dan kode
- Sebagai bahasa komunikasi
- Dapat mempercepat proses penyelesaian

## Big O Algoritm
Notasi Big-O adalah cara untuk mengekspresikan kompleksitas waktu (atau ruang) suatu algoritma. Notasi ini memberikan perkiraan kasar tentang berapa lama waktu yang dibutuhkan suatu algoritma untuk berjalan (atau berapa banyak memori yang digunakannya), berdasarkan ukuran input. Misalnya, suatu algoritma dengan kompleksitas waktuberarti waktu berjalan meningkat secara linear seiring dengan ukuran input.

## Hitung Big O dari Algoritm Sequel search

- **Time Complexty**
Kompleksitas waktu sendiri adalah ukuran seberapa lama waktu yang dibutuhkan suatu algoritma untuk berjalan, berdasarkan ukuran input. Hal ini dinyatakan menggunakan notasi Big-O, yang memberikan perkiraan kasar waktu berjalan.

- **Space Complexty**
Sedangkkan Kompleksitas ruang adalah ukuran seberapa banyak memori yang dibutuhkan suatu algoritma, berdasarkan ukuran input. Seperti kompleksitas waktu, kompleksitas ruang dinyatakan menggunakan notasi Big-O. Algoritma dengan kompleksitas ruang yang lebih rendah umumnya akan membutuhkan lebih sedikit memori daripada algoritma dengan kompleksitas ruang yang lebih tinggi.

## Referensi
- https://www.designgurus.io/blog/big-o-algorithm-complexity
- https://www.niagahoster.co.id/blog/apa-itu-pseudocode/
- https://www.tutorialspoint.com/data_structures_algorithms/binary_search_algorithm.htm
- https://dac.telkomuniversity.ac.id/algoritma-pemograman-pengertian-fungsi-dan-jenis-jenisnya/

