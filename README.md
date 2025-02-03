Home Credit - Virtual Internship (Rakamin)

Credit Risk Analyst

Project-Based Internship

Repository: GitHub - HomeCredit_Rakamin

LinkedIn: Wiefran Varenzo

📌 Problem Research

Analisis Faktor Pengajuan Pinjaman

Mengidentifikasi faktor utama yang mempengaruhi keputusan pengajuan pinjaman.

Segmentasi Pelanggan

Mengelompokkan pelanggan berdasarkan karakteristik dan perilaku mereka.

Prediksi Gagal Bayar

Menggunakan Machine Learning untuk memprediksi risiko gagal bayar pelanggan.

📊 Project Overview

Home Credit menghadapi tantangan dalam memprediksi risiko kredit secara akurat untuk memastikan pelanggan yang mampu melunasi pinjaman tidak ditolak.

Dengan menggunakan metode Machine Learning seperti Logistic Regression dan Random Forest, proyek ini bertujuan untuk:

Meningkatkan persetujuan pinjaman yang tepat.

Mengurangi risiko gagal bayar.

Meningkatkan kepuasan pelanggan dan kepercayaan terhadap Home Credit.

Hal ini penting untuk pertumbuhan bisnis dan keberlanjutan operasional Home Credit.

🔍 Data Understanding

Dataset terdiri dari:

Application Train: 122 kolom x 307.511 baris

Application Test: 122 kolom x 48.744 baris

Tantangan dalam dataset:

50 kolom memiliki lebih dari 30% missing value.

Beberapa kolom memiliki tipe data yang salah (misalnya string → integer).

🛠 Data Cleaning

Langkah-langkah yang dilakukan:

Menghapus kolom dengan >30% missing value.

Mengimputasi missing value (<30%) dengan nilai median.

Melakukan Feature Engineering

Mengubah DAYS_BIRTH menjadi AGE_YEARS.

Memastikan tidak ada duplikasi data.

Memperbaiki tipe data ID (dari integer ke string).

Menghapus kolom yang tidak informatif.

⚙️ Preprocessing

Membagi dataset menjadi data latih (train) dan data uji (test).

Melakukan encoding terhadap fitur kategori.

Melakukan scaling terhadap fitur numerik.

📈 Data Visualization & Business Insights

Faktor Risiko Berdasarkan Lama Bekerja

Semakin lama seseorang bekerja, semakin kecil risiko gagal bayar.

Klien dengan masa kerja 1-2 tahun memiliki tingkat gagal bayar 11-12%.

Klien dengan masa kerja >6 tahun memiliki tingkat gagal bayar 6-7%.

Faktor Risiko Berdasarkan Pendapatan

Klien dengan pendapatan Rp140.000-Rp180.000 memiliki tingkat gagal bayar tertinggi (0,16).

Strategi: Menyesuaikan batas kredit sesuai daya bayar pelanggan dan memberikan edukasi keuangan.

Faktor Risiko Berdasarkan Region

Region dengan rating 3 memiliki tingkat gagal bayar >0,11 (tertinggi dibandingkan region lain).

Strategi: Menerapkan kebijakan kredit lebih ketat seperti persyaratan agunan atau suku bunga berbasis risiko.

Faktor Risiko Berdasarkan Jenis Kontrak & Gender

Fitur NAME_CONTRACT_TYPE_ohe dan CODE_GENDER_ohe termasuk dalam 10 faktor terpenting yang mempengaruhi gagal bayar.

Strategi: Menyesuaikan strategi pemasaran berdasarkan jenis kontrak dan optimasi skema kredit berbasis gender.

🤖 Machine Learning Models

Model 1 - Faktor Paling Berpengaruh

Menggunakan Random Forest untuk menentukan faktor paling berpengaruh dalam gagal bayar.

Best Random Forest Model:

NumTrees: 100

MaxDepth: 7

Akurasi: 0.6840

Model 2 - Prediksi Risiko Gagal Bayar

Menggunakan Logistic Regression dan Random Forest untuk memprediksi kemungkinan gagal bayar pelanggan.

Prediksi Target:

1 → Sulit Bayar

0 → Tidak Ada Kesulitan Bayar

📽️ Video Penjelasan

Google Drive - Home Credit Virtual Internship

📌 Business Insights & Recommendations

Prioritaskan debitur dengan masa kerja lebih lama

Pelanggan dengan masa kerja >6 tahun memiliki risiko gagal bayar lebih rendah.

Strategi: Menawarkan suku bunga lebih rendah atau skema kredit khusus bagi pekerja baru dengan mitigasi risiko tambahan.

Evaluasi lebih ketat untuk pelanggan dengan pendapatan Rp140.000-Rp180.000

Tingkat gagal bayar 0,16 tertinggi dibandingkan kelompok lain.

Strategi: Menyesuaikan batas kredit dan memberikan edukasi keuangan.

Region dengan rating 3 memiliki risiko tinggi

Perlu kebijakan kredit lebih ketat, misalnya persyaratan agunan atau suku bunga berbasis risiko.

Optimalisasi strategi berdasarkan jenis kontrak dan gender

NAME_CONTRACT_TYPE_ohe dan CODE_GENDER_ohe masuk dalam 10 faktor terpenting dalam gagal bayar.

Strategi: Menyesuaikan pemasaran dan skema kredit berbasis gender untuk meningkatkan inklusivitas tanpa meningkatkan risiko gagal bayar.

📎 Referensi

Home Credit Dataset

Machine Learning Models (Logistic Regression, Random Forest)

Data Visualization & Business Insights

🚀 Contact

Untuk informasi lebih lanjut, silakan kunjungi LinkedIn - Wiefran Varenzo atau GitHub Repository.

README ini memberikan ringkasan proyek Virtual Internship Home Credit di Rakamin, mencakup pemrosesan data, visualisasi, machine learning, dan insight bisnis yang diperoleh.
