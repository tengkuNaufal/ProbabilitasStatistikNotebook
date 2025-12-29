# Tugas Besar IF2120 Probabilitas dan Statistika - Analisis Data Utility

Repository ini berisi **Tugas Besar IF2120 Probabilitas dan Statistika Tahun 2025/2026** dengan topik **Utility**. Proyek ini dilakukan oleh Kelompok 42 untuk melakukan analisis statistika deskriptif, visualisasi data, dan pengujian hipotesis terhadap dataset penggunaan utilitas (air, listrik, gas).

## 👥 Anggota Kelompok (K01 & K02 - Kelompok 42)

1. **Tengku Naufal Saqib** - 13524012
2. **Fayyaz Akmal Lauda** - 13524076

## 📂 Deskripsi File

* **`BGN_13524012_13524076.ipynb`**: File Jupyter Notebook utama yang berisi seluruh kode implementasi, analisis, dan visualisasi.
* **`utility.csv`**: Dataset yang digunakan dalam analisis (diunduh otomatis di dalam notebook).

## 📊 Tentang Dataset (`utility.csv`)

Dataset ini mencakup 5000 entri data penggunaan utilitas rumah tangga dengan kolom-kolom berikut:

* **Kolom Numerik**: `billing_month`, `avg_temperature_c`, `household_size`, `working_days`, `water_liter`, `electricity_kwh`, `gas_m3`, `water_rate`, `electricity_rate`, `gas_rate`.
* **Kolom Kategorikal**: `season`, `ownership_status`, `energy_efficiency_rating`.

## 🛠️ Prasyarat (Dependencies)

Notebook ini menggunakan pustaka Python berikut untuk analisis data dan visualisasi:

* `pandas`: Manipulasi dan analisis data frame.
* `numpy`: Operasi numerik.
* `matplotlib` & `seaborn`: Visualisasi data (grafik dan plot).
* `scipy`: Perhitungan statistik dan uji hipotesis.
* `gdown`: Mengunduh dataset dari Google Drive.

Untuk menginstal semua dependensi, jalankan perintah berikut:

```bash
pip install pandas numpy matplotlib seaborn scipy gdown

```

## 📝 Struktur Analisis

Notebook ini dibagi menjadi beberapa bagian utama sesuai dengan spesifikasi tugas:

### 1. Statistika Deskriptif (Descriptive Statistics)

* Menghitung statistik dasar (Mean, Median, Modus, Standar Deviasi, Variansi, Range, Min, Max, Kuartil, IQR, Skewness, Kurtosis) untuk data numerik.
* Menghitung frekuensi dan proporsi untuk data kategorikal.
* **Fitur Utama**: Implementasi fungsi statistik manual (buatan sendiri) dan membandingkan hasilnya dengan fungsi bawaan library (pandas/scipy) untuk memvalidasi akurasi.

### 2. Penanganan Outlier

* Mendeteksi outlier menggunakan metode **IQR (Interquartile Range)**.
* Menyajikan tabel jumlah outlier dan contoh nilai outlier untuk setiap kolom numerik.

### 3. Distribusi Data

* Menganalisis distribusi data setiap kolom menggunakan Histogram dan **Boxplot**.
* Melakukan uji normalitas menggunakan **Shapiro-Wilk Test** (dan metode lain jika relevan) untuk menentukan apakah data berdistribusi normal.

### 4. Jawaban Pertanyaan Statistika

* Menjawab berbagai pertanyaan probabilitas dan statistik berdasarkan data, seperti peluang kejadian tertentu dan korelasi antar variabel.

### 5. Pengujian Hipotesis (Hypothesis Testing)

Melakukan 6 uji hipotesis statistik yang berbeda, termasuk:

1. **Uji Hipotesis 1 sampel**: Menguji rata-rata atau proporsi terhadap nilai standar.
2. **Uji Hipotesis 2 sampel**: Membandingkan rata-rata atau variansi antara dua kelompok data.
3. **Uji Hipotesis Kategori**: Menguji proporsi atau independensi variabel kategorikal.

Setiap uji mencakup langkah-langkah formal: Penentuan H0 & H1, Tingkat Signifikansi (), Daerah Kritis, Perhitungan Statistik Uji, P-value, dan Kesimpulan.

### 6. Visualisasi Data

* Menampilkan berbagai grafik seperti Histogram, Boxplot, Scatter Plot, dan Bar Chart untuk memberikan wawasan visual yang lebih baik terhadap pola data.

## 🚀 Cara Menjalankan

1. Pastikan Python dan Jupyter Notebook sudah terinstal.
2. Buka file `BGN_13524012_13524076.ipynb`.
3. Jalankan sel pertama untuk menginisialisasi dependensi.
4. Jalankan sel "Load Data" untuk mengunduh `utility.csv` secara otomatis.
5. Jalankan sel-sel berikutnya secara berurutan untuk melihat hasil analisis.

## 📹 Tautan Video

Penjelasan visual mengenai tugas ini dapat dilihat pada tautan berikut:
[Link Video Presentasi](https://drive.google.com/file/d/16gVhLDPEDtba9cVm0PeXXGdMY25dl8IQ/view?usp=sharing)

---

*Dibuat untuk memenuhi Tugas Besar Probabilitas dan Statistika IF2120 - STIMA ITB.*
