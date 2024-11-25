---
title: Aljabar Boolean dan Gerbang Logika

---

# Aljabar Boolean dan Gerbang Logika
## Aljabar boolean
Aljabar Boolean adalah kategori aljabar yang nilai variabelnya adalah nilai kebenaran, benar dan salah, yang biasanya dilambangkan dengan 1 dan 0.
## Tujuan
- Memahami hubungan antara logika Boolean dan sirkuit komputer digital.
- Belajar cara merancang sirkuit logika sederhana.
- Memahami bagaimana sirkuit digital bekerja bersama-sama untuk membentuk sistem komputer yang kompleks.
## Operator Biner & Uner
- Operator Biner:
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

- Operator Uner:
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.


## Manfaat dalam Pemrograman
Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.


## Logic Gates (Gerbang Logika)
Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates). 

Gerbang logika adalah penyusun elektronika digital yang setiap cara kerja rangkaian pada gerbang logika menggunakan prinsip aljabar Boolean. Pada dasarnya dalam ilmu elektronik, suatu masukan dan keluaran dibangun oleh yang namanya voltase atau arus. Voltase ini biasanya dihubungkan dengan sakelar.

Oleh karena itu, gerbang logika bisa dikatakan sebagai bermacam-macam sakelar yang mengimplementasikan aljabar Boolean pada sistem elektronik. Dengan adanya sakelar, maka barang-barang elektronik tertentu bisa digunakan dengan semestinya. 


## Jenis Jenis Logic Gates.
#### Gerbang AND
Gerbang AND merupakan gerbang yang memerlukan dua atau lebih input untuk menghasilkan satu output. Jika semua atau salah satu inputnya merupakan bilangan biner 0, maka outputnya akan menjadi 0. Sedangkan jika semua input adalah bilangan biner 1, maka outputnya akan menjadi 1.



| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  0  |
|  1  |  0  |  0  |
|  0  |  1  |  0  |
|  1  |  1  |  1  |


#### Gerbang OR
gerbang OR ini sama dengan gerbang sebelumnya, gerbang ini juga memerlukan dua input untuk menghasilkan satu output. Gerbang OR ini akan menghasilkan output 1 jika semua atau salah satu input merupakan bilangan biner 1. Sedangkan output akan menghasilkan 0 jika semua inputnya adalah bilangan biner 0.

| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  0  |
|  1  |  0  |  1  |
|  0  |  1  |  1  |
|  1  |  1  |  1  |

#### Gerbang NOT
Gerbang NOT merupakan gerbang yang berfungsi sebagai pembalik keadaan. Jika input bernilai 1 maka outputnya akan bernilai 0 dan begitu juga sebaliknya.



| Input | NOT Input |
| -------- | -------- |
|  0  |  1  |
|  1  |  0  |

#### Gerbang NAND
Gerbang NAND adalah gabungan dari gerbang AND dan gerbang NOT. Maka output yang dihasilkan dari gerbang NAND ini adalah kebalikan dari gerbang AND.

| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  1  |
|  1  |  0  |  1  |
|  0  |  1  |  1  |
|  1  |  1  |  1  |

#### Gerbang NOR
Gerbang NOR adalah gabungan dari gerbang OR dan gerbang NOT. Sehingga output yang dihasilkan dari gerbang NOR ini adalah kebalikan dari gerbang OR.

| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  1  |
|  1  |  0  |  0  |
|  0  |  1  |  0  |
|  1  |  1  |  0  |

#### Gerbang XOR 
Gerbang XOR adalah gerbang yang memerlukan dua input untuk menghasilkan satu output. Jika input berbeda (misalkan: input1 =1, input2 =0) maka output yang dihasilkan adalah bilangan biner 1. Sedangkan jika input adalah sama maka akan menghasilkan output dengan bilangan biner 0.

| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  0  |
|  1  |  0  |  1  |
|  0  |  1  |  1  |
|  1  |  1  |  0  |

#### Gerbang XNOR
Gerbang XNOR adalah gerbang yang memerlukan dua input untuk menghasilkan satu output. Jika input berbeda (misalkan: input1 =1, input2 =0) maka output yang dihasilkan adalah bilangan biner 0. Sedangkan jika input adalah sama maka akan menghasilkan output dengan bilangan biner 1.

| Input 1 | input 2 | Output |
| -------- | -------- | -------- |
|  0  |  0  |  1  |
|  1  |  0  |  0  |
|  0  |  1  |  0  |
|  1  |  1  |  1  |