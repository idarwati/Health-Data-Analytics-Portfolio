# Model Transformasi Digital

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📋 Ringkasan Proyek (Project Overview)

Proyek ini mendemonstrasikan penerapan **Machine Learning** pada data sekunder rumah sakit untuk mendukung pengambilan keputusan berbasis bukti (*Evidence-Based Planning*). 

Fokus utama penelitian ini adalah mensimulasikan **Interoperabilitas** (keterhubungan) antara dua blok sistem kesehatan yang sering terpisah (silo):
1.  **Sistem Informasi Medis (EMR):** Data klinis pasien, diagnosis, dan triage.
2.  **Sistem Manajemen Sumber Daya (HR & Logistik):** Ketersediaan tempat tidur, jumlah perawat, dan biaya operasional.

Dengan menggabungkan kedua dataset ini, model memprediksi **Lama Rawat Inap (Length of Stay - LOS)** untuk mengoptimalkan efisiensi sumber daya rumah sakit.

## 🏥 Latar Belakang Masalah

Dalam kerangka *WHO Health System Building Blocks*, tantangan utama di fasilitas kesehatan Indonesia adalah fragmentasi data. Data klinis dan data operasional sering kali tidak terhubung, menyebabkan inefisiensi dalam perencanaan kapasitas (Bed Management) dan alokasi SDM.

Proyek ini menjawab tantangan tersebut dengan membangun model *Digital Transformation* sederhana namun berdampak, menggunakan pendekatan *Predictive Analytics*.

## ⚙️ Metodologi

### 1. Simulasi Data (Synthetic Data Generation)
Karena alasan privasi data pasien, proyek ini menggunakan **Synthetic Data** yang digenerate menggunakan algoritma Python untuk meniru karakteristik data riil rumah sakit:
* `data_klinis_pasien.csv`: 1.000 entri data pasien (Diagnosis ICD-10, Umur, Triage Level).
* `data_operasional_rs.csv`: Data time-series harian (Jumlah Perawat Jaga, Bed Availability).

### 2. Interoperabilitas & Pre-processing
Tahap krusial dalam proyek ini adalah proses **Data Merging** (Bridging) yang mensimulasikan integrasi antar sistem (Interoperability Simulation).
* *Teknik:* Left Join pada timestamp `Admission Date`.
* *Encoding:* One-Hot Encoding untuk variabel kategorikal (Diagnosis).

### 3. Machine Learning Modeling
* **Algoritma:** Random Forest Regressor.
* **Target Variabel:** Lama Rawat Inap (Length of Stay).
* **Evaluasi:** Mean Absolute Error (MAE) dan R-Squared.

## 📊 Hasil dan Temuan Utama



**Insight Manajerial:**
1.  **Prediksi Akurat:** Model mampu memprediksi durasi rawat inap dengan *error margin* yang rendah, memungkinkan manajer kasus (*Case Manager*) untuk memprediksi tanggal kepulangan pasien lebih awal.
2.  **Efisiensi Sumber Daya:** Dengan mengetahui prediksi LOS, manajemen dapat mengatur *Bed Turnover Interval* lebih ketat, meningkatkan pendapatan RS tanpa menambah kapasitas fisik.

## 🛠 Teknologi yang Digunakan

* **Python:** Bahasa pemrograman utama.
* **Pandas:** Manipulasi dan integrasi data (ETL).
* **Scikit-Learn:** Pembangunan model Machine Learning.
* **Seaborn/Matplotlib:** Visualisasi data untuk pelaporan.
* **Google Colab:** Environment pengembangan.

## 🚀 Cara Menjalankan (How to Run)

1.  Clone repository ini:
    ```bash
    git clone [https://github.com/username-anda/hospital-digital-transformation.git](https://github.com/username-anda/hospital-digital-transformation.git)
    ```
2.  Buka file notebook `.ipynb` menggunakan Google Colab atau Jupyter Notebook.
3.  Jalankan sel secara berurutan untuk melakukan generate data dummy dan melatih model.

## 👤 Penulis

**[Nama Anda]** *Health Administration & Policy Enthusiast | Lecturer | Data Science Learner* [Tautan Profil LinkedIn Anda]

---
*Disclaimer: Data yang digunakan dalam proyek ini adalah data sintetis (dummy) yang dibuat untuk tujuan simulasi dan pendidikan. Tidak ada data pasien asli yang digunakan.*
