# Big Data Analytics Final Project LB20

## Daftar Isi
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analisis Data](#analisis-data)
- [Penutupan](#penutupan)

## Introduction
Big Data Analytics Final Project adalah tugas akhir yang diberikan dari mata kuliah **Big Data Analytics for Business**, dilaksanakan pada semester 5 **School of Computer Science** di **Binus University**. Project ini diberikan secara berkelompok, yang masing-masing kelompok terdiri dari **2 anggota**, anggota untuk ptoject ini terdiri dari:
1. **Calvin Christian Ho**
2. **Marvin Luckianto**

## Dataset
Data yang kami ambil adalah data dari UMKM restoran *Chinese Food* yang bernama **"Sari Rasa Araya"** yang terletak di Ruko Puri Niaga Araya No. A-9. Data yang kami ambil adalah **data penjualan setiap hari dari 21 makanan yang ada di restoran tersebut, kami mengambil data mulai dari tanggal **1 November 2024 hingga 6 Desember 2024 (Sekarang)**. Isi dari data yang kami buat adalah:
- **Nama Makanan**: Nama dari makanan yang dijual
- **Kategori**: Jenis kategori dari makanan yang dijual
- **Harga**: Harga dari tiap makanan yang dijual
- **Penjualan per Hari**: Jumlah tiap makanan yang terjual setiap hari nya
- **Rata-Rata Penjualan per Bulan**: Rata-rata tiap makanan yang terjual tiap bulan
- **Total Penjualan per Hari**: Jumlah penghasilan yang didapatkan setiap hari nya, beserta rata-rata penghasilan yang didapatkan setiap bulan.

## Analisis Data
1. Bahasa Pemrograman: **Python**
2. Framework: **Google Colab**
3. Tahapan Analisis Data: **Pembuatan Dataset, Preprocessing, dan Model Algoritma**
4. Machine Learning yang Digunakan: **Naive Bayes, Support Vector Machine (SVM) K-Means, dan Clustering**

Dilakukannya Preprocessing berupa **pembersihan, tokenisasi, dan transformasi data** agar dataset dapat lebih mudah untuk di analisis. Setelah melakukan pembersihan data, kami melakukan perhitungan untuk menghitung **rata-rata penjualan per bulan nya untuk tiap kategori makanan yang tersedia**, hasil rata-rata tersebut juga di visualisasikan dalam bentuk grafik.

![image](https://github.com/user-attachments/assets/221d4e97-ae30-4fa7-a4af-210f8a29ad6d)

Kami juga melakukan perhitungan **rata-rata penjualan makanan tiap bulan dan menentukan 10 makanan dari 21 makanan yang popular dan sering dibeli oleh pelanggan**.

![image](https://github.com/user-attachments/assets/aaf7237a-8b9b-45fb-88f7-1058bb7b195b)

Kemudian dilakukannya pelatihan pada _Machine Learning Naive Bayes_ untuk memprediksi tren dari makanan yang ada di restoran tersebut. Selain itu kami juga menggunakan _Support Vecotr Machine (SVM)_ untuk mengklasifikasikan pelanggan atau transaksi ke dalam kategori yang relevan, seperti prediksi loyalitas pelanggan atau deteksi penipuan. Hasil dari data tersebut kemudian di visualisasikan.

![image](https://github.com/user-attachments/assets/adf78e00-7bc8-498e-b3d2-4db69c9e3f34)

![image](https://github.com/user-attachments/assets/7daf03db-8854-4f86-b52f-0eb064b6f8ba)

Kami juga melakukan pelatihan pada _Machine Learning K-Means_ dan _Clustering_ untuk mengelompokkan pelanggan berdasarkan preferensi atau perilaku pembelian, sehingga dapat meningkatkan strategi pemasaran dan personalisasi layanan. Hasil dari pelatihan itu telah di olah dan visualisasikan ke dalam grafik. 

![image](https://github.com/user-attachments/assets/6c1c37ac-f0dd-49c3-b16c-98bca7b67a39)

![image](https://github.com/user-attachments/assets/ca94e2bc-2be6-4558-ac74-b25554d43dd6)

Hasil dari _Machine Learning_ tersebut kemudian digunakan untuk **menampilkan dataframe yang berisikan _Distribution_, _Categorical Distributions_, _2-D Distributions_, _Time Series_, dan _Value_** dari dataset penjualan pada restoran itu. Analisis data ini dibuat untuk menampilkan data-data per bulannya, yang kemudian akan divisualisasikan dalam bentuk grafik

![image](https://github.com/user-attachments/assets/3e3c8c33-4b66-4e88-8ae0-b92a57affef4)
![image](https://github.com/user-attachments/assets/2af000cf-8667-449e-8bbf-e8a20b29dd47)
![image](https://github.com/user-attachments/assets/b8443079-8cfa-4cb1-9cf3-62e971111ff8)
![image](https://github.com/user-attachments/assets/9c4b5779-d179-4ad8-b80a-e012b291623f)
![image](https://github.com/user-attachments/assets/02d2682b-e279-4c81-908a-9ccf01bd62cb)

## Penutupan
Tujuan dari analisis data ini adalah untuk **memahami persepsi pelanggan** terhadap produk, layanan, atau merek melalui ulasan, komentar, atau masukan mereka. Dengan cara mengetahui apakah sentimen pelanggan cenderung positif, negatif, atau netral, agar dapat **mengidentifikasi kekuatan dan kelemahan serta memperbaiki strategi pemasaran**. Hasil analisis ini **membantu meningkatkan pengalaman pelanggan, membangun loyalitas, dan mendorong penjualan**.
