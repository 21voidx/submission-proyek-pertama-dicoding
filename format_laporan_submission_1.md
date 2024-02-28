# Laporan Proyek Machine Learning -  Muhammad Hafizh Trinelzy

## Domain Proyek

Proyek ini bertujuan untuk mendalami perilaku konsumen dalam belanja online dengan menganalisis data transaksi yang ada. Untuk menganalisis belanja online kunsumen, saya menggunakan dataset dari kaggle(https://www.kaggle.com/datasets/carrie1/ecommerce-data) yang berisikan seluruh transaksi antara tahun 2010 hingga 2011. 

Tujuan proyek ini dibuat adalah untuk mengefisiensi strategi pemasaran dan meningkatkan penjualan melalui segmentasi pelanggan. caranya yaitu dengan mengubah data transaksi konsumen menjadi kumpulan data yang berpusat pada pelanggan dengan menciptakan fitur baru yang dapat mensegmentasi pelanggan kedalam beberapa kelompok berbeda. 

Untuk menganalisis perilaku konsumen, saya akan menggunakan algoritma K-means. dengan melakukan clustering memungkinkan untuk memahami profil dan preferensi yang berbeda dari kelompok konsumen yang berbeda.

Tujuan akhir dari analisis ini yaitu saya akan mengembangkan sistem rekomendasi yang akan menyarankan produk terlaris kepada pelanggan setiap cluster yang belum membeli barang tersebut dan pada akhirnya dapat meningkatkan efektifitas pemasaran dan mendorong penjualan semakin pesat.

**Rubrik/Kriteria Tambahan (Opsional)**:

1. dapat memahami perilaku konsumen
2. perusahaan dapat menyesuaikan target lebih tepat dan efektif
3. membantu perusahaan memahami kebutuhan unik pasar seperti produk khusus/musiman.

## Business Understanding

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Tingkat persaingan yang tinggi terhadap pesaing. dalam pasar yang kompetitif, perusahaan harus memahami pelanggan lebih baik daripada pesaing untuk mempertahankan dan menarik pelanggan baru.
- Pelanggan yang beragam dan unik. pelanggan sering dipengaruho oleh faktor yang sulit diprediksi dengan akurat.
- strategi pemasaran menurun. perusahaan harus menggunakan strategi yang lebih tersegmentaesi dan dipersonlisasi.

### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Meningkatkan kepuasan pelanggan
- Optimasi biaya pemasaran
- Meningkatkan retensi pelanggan



**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

