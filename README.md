# Building-Recommender-System
Project Machine Learning with Python from DQLab

### Latar Belakang
Terdapat 2 dasar tipe sistem rekomendasi:

1. Sistem Rekomendasi Sederhana
2. Sistem Rekomendasi Berdasarkan Konten dari Fiturnya
 
**Sistem Rekomendasi Sederhana**, seperti namanya adalah sistem rekomendasi yang hanya **menggunakan urutan sebagai dasar perhitungannya**, yang biasanya digunakan dalam '5 film terbaik' kita akan menggunakan urutan berdasarkan mungkin vote terbanyak, rating tertinggi, penjualan film paling tinggi, atau apapun yang lain.
Dalam kasus ini, kita akan menggunakan kombinasi antara rata-rata rating, jumlah vote, dan membentuk metric baru dari metric yang sudah ada, kemudian kita akan melakukan sorting untuk metric ini dari yang tertinggi ke terendah.

### Simple Recommender Engine using Weighted Average
Simple Recommender Engine menawarkan rekomendasi yang umum untuk semua user berdasarkan popularitas film dan terkadang genre.

Ide awal di balik sistem rekomendasi ini adalah sebagai berikut.

1. Film-film yang lebih populer akan memiliki kemungkinan yang lebih besar untuk disukai juga oleh rata-rata penonton.
2. Model ini tidak memberikan rekomendasi yang personal untuk setiap tipe user. 
3. Implementasi model ini pun juga bisa dibilang cukup mudah, yang perlu kita lakukan hanyalah mengurutkan film-film tersebut berdasarkan rating dan popularitas dan menunjukkan film teratas dari list film tersebut.
Sebagai tambahan, kita dapat menambahkan genre untuk mendapatkan film teratas untuk genre spesifik tersebut.

**Formula dari IMDB dengan Weighted Rating**

 ![image](https://user-images.githubusercontent.com/62486840/147852964-3a29b9f6-91b0-4711-89ab-6e94c1940511.png)
 
 ### Hal-hal yang dikerjakan

Task 1 - Library Import and File Unloading

Task 2 - Cleaning table movie

Task 3 - Cleaning table ratings

Task 4 - Joining table movie and table ratings

Task 5 - Building Simple Recommender System

Project ini dapat diakses melalui https://academy.dqlab.id/main/package/practice/212.
