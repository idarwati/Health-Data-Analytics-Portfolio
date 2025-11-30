<a name="day-3"></a>
## 📅 Day 3: Machine Learning Prediction (Glaucoma Early Warning)
**Focus:** Supervised Machine Learning (Classification)

### 1. Problem Statement
Diagnosa Glaukoma sering terlambat karena gejala awal tidak terlihat. Tujuan model ini adalah membuat **Sistem Deteksi Dini Otomatis** berdasarkan data klinis dasar (Umur & Tekanan Intraokular).

### 2. Methodology
* **Algorithm:** Logistic Regression (Standar medis untuk prediksi biner).
* **Data Split:** 80% Training (Belajar), 20% Testing (Ujian).
* **Input Features:** Usia (Age) & IOP (Intraocular Pressure).

### 3. Model Performance 🤖
* **Accuracy:** >90% (High precision in distinguishing Glaucoma vs Normal).
* **Confusion Matrix Insight:**
    * Model berhasil meminimalisir *False Negative* (Pasien sakit tapi dibilang sehat), yang merupakan kesalahan fatal dalam diagnosa medis.
* **Prediction Simulation:**
    * *Case A (65th, IOP 25):* Predicted **Positive Glaucoma** ⚠️ (Sesuai klinis).
    * *Case B (30th, IOP 14):* Predicted **Normal** ✅.

### 4. Business Value
Model ini dapat diintegrasikan ke sistem pendaftaran RS (SIMRS). Saat perawat menginput tensi mata, sistem otomatis memberi "Red Flag" jika pasien berisiko tinggi, sehingga prioritas antrean dokter bisa disesuaikan.
