---
title: Graph

---

# Graph
 Graph merupakan kumpulan note yang saling berhubungan.
 
 ### Social Network
 Terdapat node yang mewakili  orang atau individu atau aktor. Relasi antar objek dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut *Social Network* terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk petra jaringan sosial yang dinyatakan dengan *Graph*
 
 - Tidak semua node dalam jaringan adalah penting  (aktor)
- Mencari node yang paling penting dalam suatu jaringan
- Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, yaitu
-- degree centrality, 
-- closeness centrality,
-- betweeness centrality,

### Degree Centrality 
Degree Centrality adalah jumlah *edge* yang terkoneksi pada satu node yang mewakili interaksi.

Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut

- Lebih besar derajatnya (degree), maka lebih penting node tersebut dalam suatu jaringan
- Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan

![image](https://hackmd.io/_uploads/Bkqjx1IfJl.png)
degree centrality:
![image](https://hackmd.io/_uploads/Byr1ZJ8zkg.png)
normalisasi degree centrality:
![image](https://hackmd.io/_uploads/HJEgZy8z1x.png)

Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah  
3/(9-1)=3/8.
### Closenes Centrality
Closenes Centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor *Closeness Centrality* mewakili kecepatan dalam penyebaran informasi.

Average Distance:
![image](https://hackmd.io/_uploads/HkcKbkLzyx.png)
Closeness Centrality:
![image](https://hackmd.io/_uploads/HyJJMk8Myx.png)

contoh Closeness Centrality:
![image](https://hackmd.io/_uploads/HkZLN1IMJx.png)
![image](https://hackmd.io/_uploads/Hk68NJ8zkl.png)
![image](https://hackmd.io/_uploads/Hy0F4JUfJe.png)
Node 4  lebih central  dari node 3
### Betweenness Centrality
- Skor Betweenness Centrality mewakili beberapa besar informasi yang tersebatr dari suatu aktor . Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi.

- Semakin banya lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan.

- Ukuran ini juga bisa digunakan untuk mengidentifikasi *Boundary spanners*, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas.

-- Menghitung jumlah lintasan terpendek yang melewati suatu node
-- Node dengan  betweenness  tinggi  adalah penting dalam komunikasi dan penyebaran informasi
-- Betweenness Centrality

![image](https://hackmd.io/_uploads/r1CEryUMyx.png)

Jumlah lintasan terpendek antara  s dan t
![image](https://hackmd.io/_uploads/BJmDrk8z1x.png)
Jumlah lintasan terpendek antara s dan t yang melewati vi
![image](https://hackmd.io/_uploads/HJ1KSy8Gyx.png)

Contoh Betweenness Centrality:
![image](https://hackmd.io/_uploads/rJx2SkIf1e.png)
![image](https://hackmd.io/_uploads/SJmz8y8MJl.png)
![image](https://hackmd.io/_uploads/Hkmm8kUM1g.png)
betweenness centrality  untuk node 5?

![image](https://hackmd.io/_uploads/rkuvUkUMkx.png)
Normalisasi Betweenness Centrality:
![image](https://hackmd.io/_uploads/rJ5FU18zJl.png)
