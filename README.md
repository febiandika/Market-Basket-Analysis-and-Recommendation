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
1. data/form.csv : input file
2. code/Apriori.ipynb : membuat/menguji algoritma apriori
<br>

## 2. Rekomendasi Film menggunakan Collaborative Filtering, Content-Based Filtering, dan Hybrid Filtering
<br>
## 2.1 Rekomendasi Film menggunakan Collaborative Filtering
<br>
Collaborative Filtering adalah sebuah proses penyaringan informasi dengan mengumpulkan penilaian (rating) dari seseorang (atau bisa disebut "word of mouth"). Masalah utama dari collaborative filtering adalah memprediksi seberapa baik seseorang akan menyukai sebuah item (dalam kasus ini film) yang belum pernah ia beri penilaian berdasarkan kumpulan preferensi/penilaian yang telah dilakukan sebelumnya oleh komunitas/kumpulan orang.
<br>
Selanjutnya dilakukan sebuah implementasi dari algoritma collaborative filtering menggunakan python untuk menemukan daftar rekomendasi film kepada seseorang berdasarkan penilaian yang telah dilakukan oleh orang lain.
<br>

### Daftar File
1. data/Film_Rating.csv : input file
2. code/Collaborative Filtering.ipynb : membuat/menguji algoritma Collaborative Filtering
<br>
