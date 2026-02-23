---
title: pendata

---

- Macam-Macam Data dalam Data Mining

Dalam bidang data mining dan analisis data, terdapat berbagai jenis data yang memiliki karakteristik berbeda. Setiap jenis data biasanya membutuhkan metode dan teknik pengolahan yang berbeda pula. Secara umum, data dapat diklasifikasikan menjadi:

 - Data Terstruktur

 - Data Tidak Terstruktur

 - Data Bahasa Alami

 - Data yang Dihasilkan Mesin

 - Data Audio, Video, dan Citra

 - Data Streaming

 - Data Berbasis Graph

1. Data Terstruktur (Structured Data)

Data terstruktur adalah data yang tersusun rapi berdasarkan model tertentu, biasanya dalam bentuk tabel yang terdiri dari baris dan kolom. Data ini mudah disimpan dalam database seperti MySQL atau dalam file spreadsheet seperti Excel.

Karena memiliki format yang jelas, data terstruktur mudah dilakukan proses pencarian (query), pengolahan, maupun analisis. Namun dalam kenyataannya, sebagian besar data yang dihasilkan manusia dan mesin justru berbentuk tidak terstruktur.

Atribut dalam Data

Atribut merupakan karakteristik atau ciri yang menggambarkan suatu objek data. Dalam berbagai bidang, atribut juga dikenal dengan istilah:

 - Dimensi (data warehouse)

- Fitur (machine learning)

 - Variabel (statistik)

Sekumpulan atribut yang mewakili satu objek disebut sebagai vektor atribut atau vektor fitur.

Distribusi data berdasarkan jumlah atribut dapat dibagi menjadi:

 - Univariat (1 atribut)

 - Bivariat (2 atribut)

 - Multivariat (lebih dari 2 atribut)

Jenis-Jenis Tipe Atribut
1. Atribut Nominal

Atribut nominal adalah atribut yang nilainya berupa kategori atau label tanpa adanya tingkatan.

Contoh:

Warna rambut (hitam, coklat, pirang)

Status perkawinan (lajang, menikah, bercerai)

Nilai-nilai tersebut hanya sebagai pembeda kategori dan tidak bisa dibandingkan secara urutan.

2. Atribut Biner

Atribut biner hanya memiliki dua kemungkinan nilai, biasanya 0 dan 1.

Contoh:

Status merokok (1 = merokok, 0 = tidak merokok)

Hasil tes medis (1 = positif, 0 = negatif)

Atribut biner dibagi menjadi:

Simetris → kedua nilai sama pentingnya (misal: jenis kelamin)

Asimetris → salah satu nilai lebih penting (misal: hasil tes HIV)

3. Atribut Ordinal

Atribut ordinal memiliki tingkatan atau urutan, tetapi jarak antar tingkatannya tidak diketahui secara pasti.

Contoh:

Ukuran minuman (kecil, sedang, besar)

Tingkat kepuasan (sangat tidak puas sampai sangat puas)

Atribut ordinal sering digunakan dalam survei atau penilaian subjektif.

4. Atribut Numerik

Atribut numerik bersifat kuantitatif dan dapat dihitung secara matematis.

Atribut numerik terbagi menjadi:

a. Skala Interval

Memiliki jarak yang sama antar nilai, tetapi tidak memiliki nol mutlak.

Contoh:

Suhu dalam Celsius

Tahun kalender

b. Skala Rasio

Memiliki nol absolut dan dapat dibandingkan dalam bentuk rasio.

Contoh:

Berat badan

Tinggi badan

Jumlah kata dalam dokumen

Data Tidak Terstruktur

Data tidak terstruktur adalah data yang tidak memiliki format tetap dan sulit dimasukkan ke dalam tabel.

Contoh:

Email

Dokumen teks

Komentar media sosial

Walaupun email memiliki bagian terstruktur (pengirim, subjek), isi pesannya sangat bervariasi sehingga termasuk tidak terstruktur.

Data Bahasa Alami

Bahasa alami adalah bahasa yang digunakan manusia dalam komunikasi sehari-hari seperti Bahasa Indonesia atau Bahasa Inggris.

Dalam pengolahannya diperlukan teknik Natural Language Processing (NLP) yang memadukan linguistik, statistik, dan machine learning agar komputer dapat memahami bahasa manusia.

Data yang Dihasilkan Mesin

Jenis data ini dibuat secara otomatis oleh sistem atau perangkat tanpa campur tangan manusia.

Contoh:

Log server

Data sensor IoT

Rekaman suhu dan kelembaban

Data ini biasanya terus bertambah selama sistem berjalan.

Data Berbasis Graph

Data graph menggambarkan hubungan antar objek menggunakan struktur node dan edge.

Contohnya:

Jaringan pertemanan media sosial

Relasi antar pengguna

Data ini sering digunakan untuk menganalisis hubungan dan pengaruh dalam suatu jaringan.

Data Audio, Video, dan Citra

Data multimedia seperti suara, gambar, dan video memiliki ukuran besar dan membutuhkan teknik pengolahan khusus.

Contoh pemanfaatan:

Pengenalan wajah

Pengenalan suara

Analisis citra satelit

Data Streaming

Data streaming adalah data yang masuk secara terus-menerus dalam jumlah kecil tetapi cepat.

Contoh:

Transaksi e-commerce

Log aktivitas aplikasi

Data sensor

Data ini diproses secara real-time untuk mendapatkan informasi terkini.

Distribusi Data

Distribusi data menunjukkan pola penyebaran nilai dalam suatu kumpulan data. Salah satu distribusi yang paling dikenal adalah distribusi normal (Gaussian).

Distribusi normal berbentuk kurva lonceng dengan:

Mean (rata-rata) sebagai pusat

Standar deviasi sebagai ukuran lebar penyebaran

Statistik Deskriptif

Statistik deskriptif digunakan untuk merangkum data.

Ukuran Pemusatan

Mean (rata-rata)

Median (nilai tengah)

Modus (nilai yang paling sering muncul)

Mean sensitif terhadap outlier, sedangkan median lebih stabil pada data miring.

Ukuran Penyebaran

Beberapa ukuran penyebaran data:

Range (rentang)

Kuartil

Persentil

Interquartile Range (IQR)

Variansi

Standar Deviasi

Outlier biasanya berada di bawah Q1 − 1.5 × IQR atau di atas Q3 + 1.5 × IQR.

Skewness (Kemencengan)

Skewness mengukur tingkat kemiringan distribusi data.

Skewness positif → ekor panjang ke kanan

Skewness negatif → ekor panjang ke kiri

Skewness nol → distribusi simetris

Pengukuran Jarak Data

Dalam clustering, pengukuran jarak sangat penting untuk menentukan kemiripan antar data.

Beberapa metode jarak:

 -> Minkowski Distance

 -> Manhattan Distance

 -> Euclidean Distance

 -> Mahalanobis Distance

 -> Cosine Similarity

 -> Pearson Correlation

Setiap metode memiliki kelebihan dan kekurangan tergantung tipe data yang digunakan.