# Pengembangan Model Early Warning System (EWS) Penyakit Menular Berbasis Machine Learning

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun sistem peringatan dini (Early Warning System) guna memprediksi lonjakan kasus **Demam Berdarah Dengue (DBD)** dan **Diare** di tingkat Puskesmas. Model ini memanfaatkan data historis epidemiologi dan data iklim untuk membantu Dinas Kesehatan dalam pengambilan keputusan berbasis data.

## 🎯 Tujuan
* Memprediksi tren kenaikan kasus 1 bulan ke depan.
* Mendukung manajemen sumber daya (obat, bed, nakes) sebelum KLB terjadi.
* Mengintegrasikan data **LB1 Puskesmas** dengan data **Satelit Iklim**.

## 🛠️ Metodologi & Teknologi
* **Bahasa:** Python
* **Platform:** Google Colab
* **Algoritma:** Long Short-Term Memory (LSTM) Neural Network.
* **Data Input:**
    * Data Penyakit (Time Series 5 Tahun).
    * Variabel Prediktor: Curah Hujan, Suhu, Kelembaban.

## 📊 Hasil Analisis
*(Disini Anda bisa menaruh screenshot Grafik dari Google Colab)*
Model berhasil mengikuti pola musiman kasus DBD dengan tingkat error (MAE) sebesar [X] kasus. Hal ini menunjukkan bahwa variabel iklim memiliki korelasi kuat sebagai prediktor.

## 🔗 Kontak
Dibuat oleh idar
