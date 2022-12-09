# Laporan Proyek Akhir Machine Learning Terapan - Habib Nurkholis M004X0007

## Project Overview

Ketika kita ingin mencari film bagus untuk ditonton sering kali kita mendapati bahwa terdapat banyak sekali pilihan. Hal tersebut membuat proses memilih film yang tepat membutuhkan banyak pertimbangan dan menghabiskan banyak waktu. Salah satu cara tercepat menentukan pilihan ialah dengan melihat rekomendasi.

Dari sisi pelaku bisnis khususnya jasa streaming film, mempunyai sistem rekomendasi yang baik dapat meningkatkan waktu kunjung pengguna sehingga dapat meningkatkan profit. Oleh karena itu dalam proyek ini disajikan metode untuk merekomendasikan film berdasarkan rating dari film dan hasil rekomendasi dari berbagai pengguna.

### Referensi
- G. Gupta and R. Katarya, [Recommendation Analysis on Item-based and User-Based Collaborative Filtering](https://doi.org/10.1109/ICSSIT46314.2019.8987745). 2019 International Conference on Smart Systems and Inventive Technology (ICSSIT), 2019, pp. 1-4.
- towardsdatascience.com, [Building and Testing Recommender System with Surprise - Susan Li](https://towardsdatascience.com/building-and-testing-recommender-systems-with-surprise-step-by-step-d4ba702ef80b)
- medium.com, [Recommendation System User Based Collaborative Filtering - GrabNGoInfo](https://medium.com/grabngoinfo/recommendation-system-user-based-collaborative-filtering-a2e76e3e15c4)

## Business Understanding
Proyek ini diharapkan dapat menyelesaikan beberapa permasalahan menggunakan solusi yang ditawarkan.
### Problem Statements
Adapun beberapa masalah yang ingin diselesaikan diantaranya:
- Lamanya proses pemilihan film
- Rekomendasi yang didapatkan dari teman atau orang terdekat sering kali tidak tepat dengan preferensi kita
- Pengguna pertama tidak mendapatkan rekomendasi yang baik

### Goals
Dalam penyusunan proyek ini, sistem rekomendasi yang disusun diharapkan dapat menyelesaikan permasalahan dengan kriteria tujuan sebagai berikut:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.
### Solution statements
- Menyusun sistem rekomendasi berbasis rating yang menampilkan rekomendasi top N
- Menyusun sistem rekomendasi berbasis 

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai jumlah data, kondisi data, dan informasi mengenai data yang digunakan. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya, uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data beserta insight atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model sisten rekomendasi yang Anda buat untuk menyelesaikan permasalahan. Sajikan top-N recommendation sebagai output.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menyajikan dua solusi rekomendasi dengan algoritma yang berbeda.
- Menjelaskan kelebihan dan kekurangan dari solusi/pendekatan yang dipilih.

## Evaluation
Pada bagian ini Anda perlu menyebutkan metrik evaluasi yang digunakan. Kemudian, jelaskan hasil proyek berdasarkan metrik evaluasi tersebut.

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$
