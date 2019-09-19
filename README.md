# Market Basket Analysis and Recommendation

Bagian ini terdiri dari:
<br>

## 1. Market Basket Analysis menggunakan algoritma Apriori
<br>
Market Basket Analysis adalah sebuah proses untuk menemukan frekuensi dari kumpulan-kumpulan/himpunan item pada sebuah database transaksi yang besar. Hal ini dilakukan untuk mengetahui asosiasi dan korelasi diantara para item.
<br>
Apriori adalah salah satu algoritma yang digunakan untuk market basket analysis. Apriori didesain untuk beroperasi pada database yang mengandung transaksi. Terminologi dari algoritma apriori antara lain: 
<br>
 - Support : Indikator yang menyatakan seberapa sering sebuah item muncul dalam dataset
<br> 
 - Confidence : Indikator yang menyatakan seberapa sering sebuah rule yang ditemukan bernilai benar.
<br> 
 - Lift : Nilai rasio dari nilai support yang diamati dengan ekpektasinya jika X dan Y saling bebas.
<br>
<br>
Selanjutnya dilakukan sebuah implementasi dari algoritma apriori menggunakan python untuk menemukan asosiasi dari barang/item yang diberikan.
<br>

### Daftar File
1. dataset/form.csv : input file
2. code/Apriori.ipynb : membuat/menguji algoritma apriori
<br>

## 2. Rekomendasi Film menggunakan Collaborative Filtering, Content-Based Filtering, dan Hybrid Filtering
<br>

## 2.1 Rekomendasi Film menggunakan Collaborative Filtering
<br>
Collaborative Filtering adalah sebuah proses penyaringan informasi dengan mengumpulkan penilaian (rating) dari seseorang (atau bisa disebut "word of mouth"). Masalah utama dari collaborative filtering adalah memprediksi seberapa baik seseorang akan menyukai sebuah item (dalam kasus ini film) yang belum pernah ia beri penilaian berdasarkan kumpulan preferensi/penilaian yang telah dilakukan sebelumnya oleh komunitas/kumpulan orang.
<br>
<br>
Selanjutnya dilakukan sebuah implementasi dari algoritma collaborative filtering menggunakan python untuk menemukan daftar rekomendasi film kepada seseorang berdasarkan penilaian yang telah dilakukan oleh orang lain.
<br>

### Daftar File
1. dataset/Film_Rating.csv : input file
2. code/Collaborative Filtering.ipynb : membuat/menguji algoritma Collaborative Filtering
<br>

## 2.2 Rekomendasi Film menggunakan Content-Based Filtering
<br>
Content-Based Filtering adalah sebuah proses penyaringan informasi dengan menggunakan latar belakang/deskripsi dari target user (dalam kasus ini film). Item yang digunakan dideskripsikan sebagai variabel-variabel, misal : Aktor, Sutradara, Kategori/Genre, Deskripsi Film.
<br>
<br>
Selanjutnya dilakukan sebuah implementasi dari algoritma content-based filtering menggunakan python untuk menemukan daftar rekomendasi film lain yang memiliki kemiripan dengan suatu film berdasarkan Genre, Director, dan Actors film tersebut.
<br>

### Daftar File
1. dataset/film.csv : input file
2. code/Content Based.ipynb : membuat/menguji algoritma Content-Based Filtering
<br>

## 2.3 Rekomendasi Film menggunakan Hybrid Filtering
<br>
Hybrid Filtering adalah sebuah proses penyaringan informasi dengan menggabungkan collaborative filtering dan content-based filtering.
Terdapat dua sistem yang disarankan dalam hybrid filtering, yaitu:
<br>
-Content-Based -> Collaborative
<br>
-Collaborative -> Content-Based
<br>
<br>
Selanjutnya dilakukan sebuah implementasi dari algoritma hybrid filtering menggunakan python untuk menemukan daftar rekomendasi film lain yang belum pernah ditonton oleh seorang user yang memiliki kemiripan dengan suatu film yang telah ditonton berdasarkan Genre, Director, dan Actors film tersebut dan memiliki penilaian rating yang tinggi dari user lain.
<br>

### Daftar File
1. dataset/film.csv : input file
2. dataset/Film_Rating.csv : input file
3. code/Hybrid.ipynb : membuat/menguji algoritma Hybrid Filtering
<br>

## 3. A/B Testing
<br>
A/B Testing adalah sebuah uji untuk melihat jika terdapat perbedaan signifikan secara statistika dari dua buah versi. A/B Testing digunakan dalam dunia bisnis untuk mengetahui kebiasaan pelanggan berdasar pendekatan data, bukan dengan intuisi.
<br>
<br>
Selanjutnya dilakukan sebuah implementasi dari A/B Testing menggunakan python untuk menemukan apakah terdapat perbedaan yang signifikan dari banyaknya jumlah user yang login dan checkout pada website perusahaan diantara dua buah desain website, yaitu desain A dan desain B.
<br>


### Daftar File
1. dataset/Datawebsite.csv : input file
2. code/AB Testing.ipynb : membuat/menguji AB Testing
<br>
