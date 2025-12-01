<a name="day-6"></a>
## 📉 Day 6: Patient Volume Forecasting
**Focus:** Time Series Analysis & Capacity Planning

### 1. Problem Statement
Manajemen RS seringkali bereaksi reaktif terhadap lonjakan pasien. Saya membangun model prediksi untuk mengubah pola pikir menjadi **Proaktif**. Tujuannya adalah meramal jumlah kunjungan 30 hari ke depan untuk perencanaan stok obat dan shift dokter.

### 2. Methodology
* **Data:** 1 Year historical data (Simulated daily visits).
* **Technique:** Linear Regression Trend Analysis.
* **Feature Engineering:** Converting Dates to Ordinal & capturing Weekly Seasonality.

### 3. Key Findings & Forecast 🔮
* **Trend Analysis:** Terlihat tren kenaikan positif (*Upward Trend*) sebesar ~5% per kuartal.
* **Seasonality:** Ditemukan pola penurunan signifikan (-30%) setiap akhir pekan (Weekend Effect), namun lonjakan tajam setiap hari Senin.
* **Future Forecast:** Model memprediksi rata-rata kunjungan bulan depan (Jan 2024) akan mencapai **80 pasien/hari**, meningkat dibanding rata-rata tahun lalu (65 pasien/hari).
* **Recommendation:** RS perlu meningkatkan stok farmasi sebesar 15% untuk bulan depan.
