# 📊 Superstore Profit Classifier — ML Insights Dashboard

Dashboard interaktif yang menampilkan insight dari model Machine Learning untuk mengklasifikasikan **High vs Low Profit Orders** pada dataset **Sample – Superstore**.

## 🎯 Tentang Proyek

Proyek ini merupakan mini project Tugas AI 14 yang membangun dan membandingkan 3 model klasifikasi:

| Model | Accuracy | F1-Score | ROC-AUC |
|-------|----------|----------|---------|
| Logistic Regression | 94.25% | 96.49% | 98.18% |
| Random Forest | 94.05% | 96.43% | 98.29% |
| **XGBoost** ⭐ | **94.35%** | **96.55%** | **98.65%** |

**XGBoost** terpilih sebagai model terbaik dengan performa paling seimbang di seluruh metrik evaluasi.

## 🔍 Fitur Dashboard

- **Ringkasan Dataset** — Overview statistik dataset Superstore (9.994 transaksi)
- **Exploratory Data Analysis** — Distribusi target & korelasi fitur
- **Perbandingan Model** — Tabel & chart metrik evaluasi 3 model
- **Best Model Highlight** — Metrik XGBoost dengan progress bar
- **Feature Importance** — Top 10 fitur berpengaruh (XGBoost)
- **Cross-Validation** — Radar chart & tabel 5-fold CV
- **Key Insights** — 6 temuan utama dari analisis
- **Kesimpulan** — Paragraf kesimpulan komprehensif
- **Download Dataset** — Unduh file CSV langsung dari dashboard

## 🛠️ Teknologi

- **HTML5** — Struktur semantik
- **CSS3** — Dark theme, glassmorphism, animasi, responsive
- **JavaScript** — Logika visualisasi
- **[Chart.js](https://www.chartjs.org/)** — Library chart interaktif (via CDN)
- **[Google Fonts](https://fonts.google.com/)** — Font Inter

## 📁 Struktur File

```
dashboard/
├── index.html                  # Halaman utama dashboard
├── css/
│   └── style.css               # Styling (dark theme, glassmorphism)
├── js/
│   └── charts.js               # Visualisasi Chart.js
├── Sample - Superstore.csv     # Dataset untuk download
├── README.md                   # Dokumentasi proyek
└── .gitignore                  # File yang dikecualikan dari git
```

## 🚀 Cara Menjalankan

1. **Clone repository**
   ```bash
   git clone https://github.com/username/superstore-profit-dashboard.git
   cd superstore-profit-dashboard
   ```

2. **Buka langsung di browser**
   ```
   Klik dua kali file index.html
   ```

   Atau gunakan live server:
   ```bash
   # Menggunakan Python
   python -m http.server 3000

   # Menggunakan Node.js
   npx serve . -l 3000
   ```

3. **Akses dashboard** di `http://localhost:3000`

## 👥 Kelompok 3

| Nama | NPM |
|------|-----|
| Fabio Banyu Cyto | 123450104 |
| Gusti Putu Ferazka D. | 123450046 |
| Aliya Ammara Ananta | 123450075 |
| Hafsa Fazila Arradhi | 123450079 |

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik — Tugas AI 14.
