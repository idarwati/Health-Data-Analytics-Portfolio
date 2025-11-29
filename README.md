# # 🏥 Health Data Analytics Portfolio
**Author:** Idarwati  
**Role:** Health Administrator & Lecturer | Aspiring Data Analyst  
**Focus:** Ophthalmology, Public Health, & Hospital Efficiency

---

## 📌 Project Roadmap (Journey Log)
Berikut adalah dokumentasi perjalanan saya mempelajari Data Science untuk kesehatan dalam 1 bulan:

* **[Minggu 1: Hospital Operations & Risk Analysis](#week-1)**
    * [Day 1: Optimizing Eye Hospital Resources (Descriptive Analysis)](#day-1)
    * [Day 2: Validating Clinical Risk Factors (Statistical Inference)](#day-2)

---

<a name="week-1"></a>
# 📅 WEEK 1: Hospital Operations & Risk Analysis

<a name="day-1"></a>
## 🚀 Day 1: Optimizing Eye Hospital Resources
**Focus:** Descriptive Analytics & Visualization

### 1. Latar Belakang (Background)
Sebagai administrator kesehatan, saya melihat perlunya keputusan berbasis data. Proyek ini mensimulasikan data operasional RS Mata (n=500) untuk menganalisis hambatan layanan.

### 2. Key Insights 📊
* **Poli Katarak** memiliki volume pasien tertinggi (~35%), menjadi titik kritis antrean.
* **Segmentasi Umur:** Poli Glaukoma didominasi pasien Geriatri (>60 th), sedangkan Poli Retina & Infeksi didominasi usia produktif.
* **Rekomendasi:** Penerapan "Dynamic Staffing" di poli Katarak pada jam sibuk.

---

<a name="day-2"></a>
## 🧪 Day 2: Validating Clinical Risk Factors
**Focus:** Statistical Hypothesis Testing (Inferential Statistics)

### 1. Objective
Setelah melihat pola visual di Day 1, hari ini saya menggunakan uji statistik untuk membuktikan apakah hubungan antar variabel klinis bersifat signifikan atau hanya kebetulan.

### 2. Statistical Findings 🧮
Saya menggunakan Python (`Scipy`) untuk melakukan uji hipotesis:

#### A. Intraocular Pressure (IOP) & Glaucoma (T-Test)
* **Hypothesis:** Apakah tekanan mata pasien Glaukoma berbeda signifikan dengan pasien Normal?
* **Result:** P-Value < 0.05 (Signifikan).
* **Insight:** Rata-rata TIO pasien Glaukoma (~20.4 mmHg) secara statistik lebih tinggi dibanding pasien normal. Ini memvalidasi TIO sebagai indikator skrining utama.

#### B. Diabetes & Retinopathy (Chi-Square Test)
* **Hypothesis:** Apakah riwayat Diabetes berhubungan dengan kejadian Retinopati?
* **Result:** P-Value < 0.05 (Signifikan).
* **Insight:** Ada ketergantungan kuat (strong dependency) antara Diabetes dan kerusakan retina.
* **Actionable Plan:** RS wajib menerapkan protokol skrining fundus otomatis bagi setiap pasien berstatus Diabetes di pendaftaran.

---
*Repository ini akan terus diupdate setiap hari selama tantangan 30 hari.*
