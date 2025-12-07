# 🏥 Analisis Sentimen Layanan Kesehatan Masyarakat (Public Health Sentiment Analysis)

> **Project Status:** Completed  
> **Domain:** Public Health, Health Informatics, Data Analytics  
> **Tools:** Python (Pandas, Matplotlib, Seaborn, WordCloud)

## 📖 Latar Belakang (Background)
Dalam manajemen pelayanan kesehatan, umpan balik (*feedback*) pasien adalah data krusial untuk evaluasi kualitas layanan. Metode konvensional seperti kotak saran fisik seringkali lambat dan tidak terstruktur.

Proyek ini bertujuan untuk mensimulasikan **Digital Health Surveillance** sederhana. Saya menggunakan Python untuk menganalisis keluhan dan kepuasan pasien terhadap layanan Puskesmas berdasarkan data media sosial tiruan (*dummy data*).

Sebagai seorang profesional di bidang **Administrasi & Kebijakan Kesehatan**, tujuan saya adalah mendemonstrasikan bagaimana data tidak terstruktur (teks) dapat diubah menjadi wawasan (*insight*) untuk pengambilan keputusan strategis.

## 🎯 Tujuan (Objectives)
1.  Melakukan **Data Generation** (simulasi data) untuk meniru pola komentar media sosial terkait layanan kesehatan.
2.  Melakukan **Analisis Sentimen** sederhana untuk mengklasifikasikan komentar menjadi Positif, Negatif, atau Netral.
3.  Memvisualisasikan data menggunakan **Word Cloud** dan **Bar Chart** untuk memudahkan pembacaan oleh pemangku kebijakan.

## 🛠️ Metodologi & Tools
Proyek ini dikerjakan menggunakan **Google Colab**. Langkah-langkah yang dilakukan:

1.  **Data Simulation:** Membuat 100+ dataset artifisial yang mencakup berbagai topik (Antrian, Dokter, Fasilitas, Obat).
2.  **Preprocessing:** Membersihkan teks (Case folding).
3.  **Sentiment Logic:** Menggunakan pendekatan *Rule-Based* (Kamus Kata) untuk menentukan sentimen.
4.  **Visualization:**
    * `Pandas`: Manipulasi data.
    * `Matplotlib & Seaborn`: Grafik batang distribusi sentimen.
    * `WordCloud`: Visualisasi topik dominan.

## 📊 Temuan Utama (Key Insights)
Berdasarkan hasil simulasi data, ditemukan pola yang relevan dengan masalah kesehatan riil:

* **Isu Administratif vs Medis:** Sentimen negatif cenderung tinggi pada aspek operasional (kata kunci: *"Antrian"*, *"Lama"*, *"Ribet"*).
* **Kepuasan Pelayanan:** Sentimen positif dominan pada interaksi personal dengan tenaga kesehatan (kata kunci: *"Dokter"*, *"Ramah"*).
* **Rekomendasi Kebijakan:** Perbaikan tidak harus difokuskan pada kompetensi medis, melainkan pada **rekayasa alur pendaftaran** dan **manajemen waktu tunggu**.

## 📷 Visualisasi (Preview)

*(Upload screenshot WordCloud atau Grafik Anda di sini)*

## 🚀 Cara Menjalankan (How to Run)
Anda bisa melihat dan menjalankan kode ini langsung melalui Google Colab:

[**🔗 Link ke Google Colab Notebook**](MASUKKAN_LINK_GOOGLE_COLAB_ANDA_DISINI)

---
**Author:** [Nama Anda]  
*Health Administration & Policy Enthusiast | Aspiring Health Data Analyst* [Tautkan ke LinkedIn Anda Disini]
