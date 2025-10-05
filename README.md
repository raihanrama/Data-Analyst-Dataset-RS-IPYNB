# Hospital Data Analysis Project 🏥

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Looker Studio](https://img.shields.io/badge/Looker-Studio-4285F4.svg)](https://lookerstudio.google.com/)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

## 📋 Deskripsi Proyek

Proyek ini merupakan analisis komprehensif terhadap data rumah sakit yang mencakup seluruh siklus analisis data, mulai dari pengumpulan data, pembersihan, analisis, hingga visualisasi dalam bentuk dashboard interaktif. Tujuan utama adalah memberikan insights yang actionable untuk meningkatkan efisiensi operasional rumah sakit dan kualitas pelayanan pasien di rumah sakit.

## 🎯 Tujuan Proyek

- **Menganalisis pola kunjungan pasien** dan tren historis
- **Mengidentifikasi faktor-faktor** yang mempengaruhi tingkat okupansi
- **Mengoptimalkan alokasi sumber daya** yang terdapat dirumah sakit
- **Memberikan rekomendasi strategis** berdasarkan data
- **Membuat dashboard interaktif** untuk monitoring real-time

## 🛠️ Teknologi yang Digunakan

### Programming & Analysis
- **Python 3.8+** - Bahasa pemrograman utama
- **Jupyter Notebook** - Environment untuk analisis interaktif
- **Pandas** - Manipulasi dan analisis data
- **NumPy** - Komputasi numerik
- **Matplotlib & Seaborn** - Visualisasi data
- **Plotly** - Visualisasi interaktif
- **Scikit-learn** - Machine learning 

### Visualization & Reporting
- **Looker Studio** - Dashboard dan pelaporan

## 📊 Dataset

Dataset yang digunakan dalam proyek ini mencakup:

- **Informasi Pasien**: Data demografis, jenis kelamin, usia
- **Data Kunjungan**: Tanggal masuk, keluar, lama rawat inap
- **Departemen**: Jenis layanan, spesialisasi medis
- **Kapasitas**: Jumlah tempat tidur, tingkat okupansi
- **Finansial**: Biaya perawatan, metode pembayaran

> **Catatan**: Semua data telah dianonimisasi dan mengikuti protokol privasi yang ketat.


## 📈 Metodologi Analisis

### 1. **Data Collection & Acquisition**
- Pengumpulan data dari berbagai sumber rumah sakit
- Validasi kualitas dan kelengkapan data
- Dokumentasi metadata dan data dictionary

### 2. **Data Preprocessing**
- **Data Cleaning**: Penanganan missing values, outliers
- **Data Transformation**: Normalisasi, encoding categorical variables
- **Feature Engineering**: Pembuatan variabel baru yang relevan
- **Data Integration**: Penggabungan dari multiple sources

### 3. **Exploratory Data Analysis (EDA)**
- Analisis deskriptif statistik
- Identifikasi pola dan tren
- Korelasi antar variabel
- Segmentasi pasien dan layanan

### 4. **Statistical Analysis**
- Hypothesis testing
- Time series analysis
- Predictive modeling (jika applicable)
- Performance metrics calculation

### 5. **Visualization & Dashboard**
- Pembuatan visualisasi insights
- Development dashboard Looker Studio
- Interactive reporting setup

## 📊 Key Findings & Insights

### 🏥 Okupansi & Kapasitas
- Tingkat okupansi rata-rata: **XX%**
- Peak hours: **XX:XX - XX:XX**
- Departemen dengan okupansi tertinggi: **[Nama Departemen]**

### 👥 Profil Pasien
- Distribusi usia: Mayoritas **XX-XX tahun**
- Gender distribution: **XX%** perempuan, **XX%** laki-laki
- Average length of stay: **X.X hari**

### 📅 Pola Temporal
- Hari tersibuk: **[Hari]**
- Musim peak: **[Bulan/Season]**
- Growth rate tahunan: **+X.X%**

### 💰 Aspek Finansial
- Revenue per patient: **Rp XXX,XXX**
- Cost efficiency metrics
- Payment method preferences

## 🎨 Dashboard Looker Studio

Dashboard interaktif telah dibuat dengan fitur-fitur:

### 📊 **Overview Dashboard**
- KPI utama rumah sakit
- Trend okupansi real-time
- Revenue tracking

### 🏥 **Operational Dashboard**
- Capacity utilization by department
- Patient flow analysis
- Staff allocation metrics

### 👨‍⚕️ **Clinical Dashboard**
- Patient demographics
- Treatment outcomes
- Length of stay analysis

### 💹 **Financial Dashboard**
- Revenue analysis
- Cost breakdown
- Profitability metrics


## 🚀 Cara Menjalankan Proyek

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
Git
```

### Installation
```bash
# Clone repository
git clone https://github.com/raihanrama/Data-Analyst-Dataset-RS-IPYNB.git
cd Data-Analyst-Dataset-RS-IPYNB

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

### Running the Analysis
1. Mulai dengan `01_data_exploration.ipynb`
2. Lanjutkan secara berurutan ke notebook berikutnya
3. Jalankan dashboard setup untuk Looker Studio integration

## 📋 Requirements

```txt
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.0.0
scikit-learn>=1.0.0
jupyter>=1.0.0
openpyxl>=3.0.0
requests>=2.25.0
```

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

1. Fork repository ini
2. Buat feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push ke branch (`git push origin feature/amazing-feature`)
5. Buat Pull Request

## 📧 Kontak

**Muhammad Raihan Ramadhan**
- 📧 Email: [muhammadraihan291003@gmail.com](mailto:muhammadraihan291003@gmail.com)
- 💼 LinkedIn: [Muhammad Raihan Ramadhan](https://www.linkedin.com/in/muhammad-raihan-ramadhan-3735b5293/)
- 🐱 GitHub: [@raihanrama](https://github.com/raihanrama)

## 📄 Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail.

---

**⭐ Jika proyek ini bermanfaat, jangan lupa berikan star!**

> *"Data is the new oil, but insights are the refined fuel for decision making."*

---

### 📊 Project Stats
![GitHub last commit](https://img.shields.io/github/last-commit/raihanrama/Data-Analyst-Dataset-RS-IPYNB)
![GitHub issues](https://img.shields.io/github/issues/raihanrama/Data-Analyst-Dataset-RS-IPYNB)
![GitHub stars](https://img.shields.io/github/stars/raihanrama/Data-Analyst-Dataset-RS-IPYNB)

**Last Updated**: Oktober 2025
