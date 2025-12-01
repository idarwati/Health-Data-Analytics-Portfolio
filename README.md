<a name="day-4"></a>
## 🗺️ Day 4: Geospatial Analysis (Patient Accessibility Mapping)
**Focus:** Spatial Epidemiology & GIS Visualization

### 1. Problem Statement
Data alamat pasien seringkali hanya menjadi teks mati. Saya mengubah data koordinat pasien menjadi **Peta Interaktif** untuk melihat korelasi antara *Jarak Tempat Tinggal* dengan *Tingkat Keparahan Penyakit* saat datang ke RS.

### 2. Methodology
* **Tools:** `Folium` (Python Library for Leaflet Maps).
* **Technique:** Coordinate Mapping & Heatmap Density visualization.
* **Location Scope:** Simulated patient data in Makassar area.

### 3. Key Spatial Insights 🌍
* **Accessibility Issue:** Visualisasi peta memperlihatkan pola *Centrifugal*. Pasien yang tinggal di radius luar (>10km dari RS) didominasi oleh titik **Merah** (Datang dalam kondisi Berat/Lanjut).
* **Hotspots:** *Heatmap* menunjukkan konsentrasi pasien tertinggi bukan berasal dari pusat kota, melainkan dari area padat penduduk di sisi Timur.
* **Policy Recommendation:** RS perlu mengadakan "Mobile Clinic" atau Skrining Keliling di area *Hotspot* pinggiran kota untuk menjaring pasien lebih awal.
