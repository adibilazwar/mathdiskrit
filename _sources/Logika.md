---
title: Logika

---

# Logika Matematika

## Negasi
Negasi adalah suatu penolakan atau ingkaran dari pernyataan yang ada. Jika sebuah pernyataan bernilai salah maka negasinya bernilai benar dan jika pernyataan bernilai benar maka negasinya bernilai salah. Penulisan lambang negasi P
adalah $\neg p$. Untuk menentukan negasi atau ingkaran dari sebuah pernyataan, maka penulisan ditambah kata “ tidak , tidak benar bahwa, atau bukan“ di depan pernyataan tersebut.


| p    | $\neg p$ |
| -------- | ------
| T    | F     |
| F    | T     |

| p    | $\neg p$ |
| -------- | ------
| 1    | 0     |
| 0    | 1     |

*Contoh*:
- P= 2 Adalah bilangan prima (B)
- $\neg p$= 2 Adalah bukan bilangan prima (S)
- Farhan adalah anak seorang buronan (B)
- Farhan adalah bukan anak seorang buronan (S)

Negasi dari pernyataan ekuivalen dengan disjungsi dari masing-masing konjungsinya dan begitu sebaliknya. Bentuk kesetaraan di atas disebut juga dengan pernyataan De-Morgan, yaitu :

~(P$\wedge$Q) = ~P $\vee$ ~Q
~(P$\vee$Q) = ~P $\wedge$ ~Q

Selain pernyataan De-Morgan masih banyak kesetaraan yang lain, misalnya :

~(P$\rightarrow$Q) = P$\wedge$~Q
~(P$\leftrightarrow$Q) = (P$\wedge$ ~Q) $\vee$ (Q$\wedge$ ~P)

*Contoh=* 
- 4 merupakan bilangan genap dan bulat.
Negasinya ada 2 kemungkinan, yaitu :
  1. Tidak benar bahwa 4 merupakan bilangan genap dan bulat.
  2.  4 merupakan bukan bilangan genap atau bukan bilangan bulat.
  
- Kita dapat berbelanja di Toko Restu Mertua atau di Uniqlo Dept. Store.
Negasinya ada 2 kemungkinan, yaitu :
  1. Tidak benar bahwa kita dapat berbelanja di Toko Restu Mertua atau di Uniqlo Dept. Store.
  2. Kita dapat berbelanja tidak di Toko Restu Mertua dan tidak di Uniqlo Dept. Store

## Konjuksi
Jika dua pernyataan digabungkan dengan kata “dan” maka pernyataan itu disebut konjungsi. Penulisan kata gabung “dan “ pada konjungsi dilambangkan dengan tanda : “ $\wedge$ ". Sedangkan tabel kebenaran pernyataan-pernyataan konjungsi disampaikan dalam bentuk tabel sebagai berikut :



| P   | Q   | P$\wedge$Q |
| --- | --- | ---------- |
| B   | B   | B          |
| B   | S   | S          |
| S   | B   | S          |
| S   | S   | S          |

        
| P   | Q   | P$\wedge$Q |
| --- | --- | ---------- |
| 1   | 1   | 1          |
| 1   | 0   | 0          |
| 0   | 1   | 0          |
| 0   | 0   | 0          |

Pernyataan majemuk P$\wedge$Q dikatakan benar jika kedua-duanya benar dalamhal lain yang dikatakan salah
*Contoh*=
- P= Harimau adalah hewan Buas (B)
- Q= Harimau adalah hewan pemakan daging (B)
- P$\wedge$Q= Harimau adalah hewan buas pemakan daging

## Disjungsi
Jika dua pernyataan digabungkan dengan kata “ atau “ maka pernyataan majemuk ini disebut disjungsi. Disjungsi mempunyai dua arti yang berbeda yaitu: 
(1) Disjungsi Inklusif dan (2) Disjungsi Eksklusif
 Disjungsi inklusif mempunyai makna benar jika paling sedikit satu daripernyataan bernilai benar.Lambang disjungsi inklusif adalah 
 “ $\vee$ “ dan tabel kebenarannya sebagai
berikut.

| P   | Q   | P$\vee$Q |
| --- | --- | ---------- |
| B   | B   | B          |
| B   | S   | B          |
| S   | B   | S          |
| S   | S   | S          |



## Implikasi
Pernyataan majemuk yang berbentuk “ jika P maka Q “ disebut implikasi atau kondisional. Lambang penulisan implikasi sebagai berikut :
“ P $\rightarrow$ Q“
Pernyataan majemuk “ P$\rightarrow$Q “ akan dikatakan bernilai salah jika P benar dan Q salah, dalam hal lain dikatakan benar.
Tabel kebenaran dari implikasi sebagai berikut 


| P   | Q   | P$\rightarrow$Q |
| --- | --- | ---------- |
| B   | B   | B          |
| B   | S   | S          |
| S   | B   | B          |
| S   | S   | B          |
## Biimplikasi

Pernyataan majemuk yang berbentuk “ P jika dan hanya jika Q “ disebut Bi-implikasi. Penulisan Bi-implikasi menggunakan lambang “ P$\leftrightarrow$Q “. Lambang di atas bermakna :
1. P jika dan hanya jika Q.
2. P ekuivalen Q.
3. P syarat yang perlu dan cukup untuk Q.
Jika P dan Q dua pernyataan yang tersusun sebagai “P Q “ maka tabel
kebenarannya sebagai berikut:

| P   | Q   | P$\rightarrow$Q |
| --- | --- | ---------- |
| B   | B   | B          |
| B   | S   | S          |
| S   | B   | S          |
| S   | S   | B          |

*Soal:*
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

\begin{array}{c|c|c|c|c|c}
P & Q & R & R \to Q & P \lor (R \to Q) \\
\hline
\text{T} & \text{T} & \text{T} & \text{T} & \text{T} \\
\text{T} & \text{T} & \text{F} & \text{T} & \text{T} \\
\text{T} & \text{F} & \text{T} & \text{F} & \text{T} \\
\text{T} & \text{F} & \text{F} & \text{T} & \text{T} \\
\text{F} & \text{T} & \text{T} & \text{T} & \text{T} \\
\text{F} & \text{T} & \text{F} & \text{T} & \text{T} \\
\text{F} & \text{F} & \text{T} & \text{F} & \text{F} \\
\text{F} & \text{F} & \text{F} & \text{T} & \text{T} \\
\end{array}