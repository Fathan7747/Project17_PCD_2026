# Klasifikasi Tingkat Kematangan Biji Kopi Berbasis Ekstraksi Fitur Tekstur GLCM dengan Perbandingan Algoritma KNN, SVM, dan Random Forest

## Nama Anggota

### Septian Dwi Putra : F1D022160
### Felyvia Trevina Gunawan : F1D02410112
### Annisa Makrima Ahlaq : F1D02410106
### Muhammad Fathan Abdullah : F1D02410124

# Project Overview

Kopi merupakan salah satu komoditas pertanian yang memiliki nilai ekonomi tinggi dan banyak dikonsumsi di berbagai negara. Kualitas kopi sangat dipengaruhi oleh tingkat kematangan biji kopi, karena kematangan yang berbeda akan menghasilkan karakteristik rasa, aroma, serta kualitas produk akhir yang berbeda pula. Namun, proses identifikasi tingkat kematangan biji kopi masih sering dilakukan secara manual melalui pengamatan visual, sehingga hasilnya cenderung subjektif dan bergantung pada pengalaman pengamat. Oleh karena itu, diperlukan suatu sistem klasifikasi otomatis yang mampu membantu proses identifikasi tingkat kematangan biji kopi secara lebih cepat, konsisten, dan akurat.

Pada proyek ini dilakukan klasifikasi tingkat kematangan biji kopi menggunakan pendekatan pengolahan citra digital dan machine learning. Dataset yang digunakan terdiri dari empat kelas tingkat kematangan, yaitu Green, Light, Medium, dan Dark. Sebelum dilakukan proses klasifikasi, citra terlebih dahulu melalui tahap preprocessing yang meliputi resize, grayscale, median filter, dan Gaussian blur. Tahap preprocessing memiliki peran yang sangat penting karena bertujuan untuk menyeragamkan ukuran citra, mengurangi noise, serta meningkatkan kualitas data yang akan digunakan pada tahap selanjutnya. Dengan citra yang lebih bersih dan konsisten, proses ekstraksi fitur dapat menghasilkan informasi yang lebih representatif terhadap karakteristik biji kopi.

Setelah preprocessing, dilakukan ekstraksi fitur tekstur menggunakan metode Gray Level Co-occurrence Matrix (GLCM). Metode ini dipilih karena mampu merepresentasikan karakteristik tekstur permukaan biji kopi melalui hubungan antar piksel pada citra grayscale. Dari matriks GLCM diekstraksi berbagai fitur tekstur seperti contrast, dissimilarity, homogeneity, energy, correlation, dan entropy pada beberapa arah pengamatan. Tahap ekstraksi fitur merupakan bagian penting dalam sistem klasifikasi karena berfungsi mengubah informasi visual pada citra menjadi data numerik yang dapat dipahami dan diproses oleh algoritma machine learning.

Fitur-fitur hasil ekstraksi kemudian digunakan sebagai masukan bagi tiga algoritma klasifikasi, yaitu K-Nearest Neighbor (KNN), Support Vector Machine (SVM), dan Random Forest. Ketiga algoritma tersebut dipilih untuk dibandingkan performanya dalam mengklasifikasikan tingkat kematangan biji kopi. KNN mewakili metode klasifikasi berbasis kedekatan jarak data, SVM mewakili metode berbasis pemisahan ruang fitur yang optimal, sedangkan Random Forest mewakili metode ensemble yang menggabungkan banyak pohon keputusan. Perbandingan dilakukan menggunakan metrik evaluasi seperti accuracy, precision, recall, F1-score, serta confusion matrix untuk mengetahui model yang memberikan hasil terbaik.

Melalui proyek ini diharapkan dapat diperoleh model klasifikasi yang mampu mengenali tingkat kematangan biji kopi secara akurat berdasarkan karakteristik teksturnya. Selain itu, penelitian ini juga menunjukkan pentingnya tahap preprocessing dan ekstraksi fitur dalam meningkatkan kualitas data masukan sehingga dapat membantu algoritma machine learning menghasilkan performa klasifikasi yang lebih optimal.
