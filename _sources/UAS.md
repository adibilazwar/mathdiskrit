---
title: UAS

---

# UAS 

### Soal 1
| P | Q | R | S   |
| -------- | -------- | -------- | -------- |
|  1  |  0  |  1  |  1  |
|  0  |  0  |  1  |  1  |
|  1  |  0  |  1  |  0  |
|  1  |  0  |  1  |  1  |
|  0  |  1  |  1  |  1  |
|  0  |  1  |  0  |  0  |
|  1  |  1  |  1  |  1  |
|  0  |  0  |  1  |  0  |

(P$\rightarrow$Q) $\rightarrow$ (R$\rightarrow$S)

#### jawaban no 1
 | P   | Q   | P$\rightarrow$Q |
| --- | --- | ---------- |
| B   | S   | S          |
| S   | S   | S          |
| B   | S   | S          |
| B   | S   | S          |
| S   | B   | S          |
| S   | B   | S          |
| B   | B   | B          |
| S   | S   | S          |

(P$\rightarrow$Q)= S


 | R   | S   | R$\rightarrow$S |
| --- | --- | ---------- |
| B   | B   | B          |
| B   | B   | B          |
| B   | S   | S          |
| B   | B   | B          |
| B   | B   | B          |
| S   | S   | S          |
| B   | B   | B          |
| B   | S   | S          |

(R$\rightarrow$S)= B

jadi:
(P$\rightarrow$Q) $\rightarrow$ (R$\rightarrow$S)= S (salah)


### soal 2
![Screenshot 2024-12-09 134524](https://hackmd.io/_uploads/rySVzf4Vkg.png)
- Hitung Closenes Centrality dari G
- Hitung Betweenness Centrality dari F

#### jawaban no 2
- Mencari Closenes Centrality
$C_c(v) = \frac{n - 1}{\sum_{u \neq v} d(u, v)}$

jumlah simpul n = 7 (A,B,C,D,E,F,G)
hitung jarak terpendek dari G ke semua sisi =
-- d(G,A)= 3 (G$\rightarrow$E$\rightarrow$D $\rightarrow$A)
-- d(G,B)= 4 (G$\rightarrow$E$\rightarrow$D$\rightarrow$A$\rightarrow$B)
-- d(G,C)= 3 (G$\rightarrow$E$\rightarrow$D$\rightarrow$C)
-- d(G,D)= 2 (G$\rightarrow$E$\rightarrow$D)
-- d(G,E)= 1 (G$\rightarrow$E)
-- d(G,F)= 2 (G$\rightarrow$E$\rightarrow$F)

total jarak =

$\sum_{u \neq G} d(u, G) = 3 + 4 + 3 + 2 + 1 + 2 = 15$

Closenes Centrality =

$C_c(G) = \frac{7 - 1}{15}=  \frac{6}{15}=0.4$

- Mencari Betweenness Centrality
$C_b(F) = \sum_{s \neq v \neq t} \frac{\sigma_{st}(F)}{\sigma_{st}}$

Langkah pertama yang harus dilakukan yaitu mencari kombinasi pasangan dengan F di jalur terpendek, yaitu:

--(A,F): $\frac{1}{1}$ = 1
--(B,F): $\frac{1}{1}$ = 1
--(C,E): $\frac{1}{1}$ = 1
--(C,G): $\frac{1}{1}$ = 1

Betweenness Centrality=
$C_c(F) =1+1+1+1=4$

