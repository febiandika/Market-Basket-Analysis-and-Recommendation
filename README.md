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
