# Title Project
Analisis Tren Pemakaian Obat di RSUD Kota Bandung Tahun 2015-2024 dengan IBM Granite

# Raw dataset link
https://opendata.bandung.go.id/dataset/jumlah-pemakaian-obat-farmasi-berdasarkan-jenis-obat-dan-jenis-perawatan-di-rsud-kota-bandung-2

# Project overview
Capstone project yang berfokus pada analisis data penggunaan obat generik dan non-generik. Data mentah berasal dari file Excel, kemudian diproses menggunakan Python (pandas, matplotlib) dan IBM Granite. 

Tools yang digunakan : 
- Google Colab untuk implementasi kode
- Python (pandas, matplotlib) untuk pengolahan dan visualisasi data
- IBM Granite LLM untuk klasifikasi tren, ringkasan, dan rekomendasi

# Analysis Process
1. Persiapan lingkungan dan instalasi : instalasi dan import library
2. Konfigurasi dan autentikasi API : Mengambil token API dan inisialisasi model
3. Pemrosesan data awal : Load data dan pembersihan data
4. Analisis dan agregasi data : Pengelompokan data berdasarkan tahun, jenis perawatan, serta gabungan
5. Klasifikasi dengan IBM Granite : Menyiapkan prompt dan mengirim ke model
6. Visualisasi dengan matplotlib (line plot dan bar plot)
7. Rekomendasi dengan IBM Granite : Menyiapkan prompt dan mengirim ke model

# Insight and Findings
Hasil yang didapatkan : 
- Tabel agregasi penggunaan obat per tahun, per ruangan, dan gabungan
- Klasifikasi tren penggunaan obat generik dan non-generik per tahun maupun per ruangan
- Ringkasan singkat yang menyoroti pola utama dari data
- Rekomendasi berbasis tren yang dapat membantu evaluasi penggunaan obat
- Line plot dan bar plot analisis tren

# Conclusion and Recommendations
- IBM Granite dapat digunakan untuk mengklasifikasikan tren penggunaan obat, baik berdasarkan jenis perawatan maupun periode waktu.
- Model ini mampu membuat ringkasan dari data, sehingga memudahkan dalam memahami pola yang terjadi.
- IBM Granite juga bisa memberikan rekomendasi umum terkait perubahan tren yang ditemukan.
- Hasil menunjukkan Granite cukup efektif sebagai pendukung analisis data ketika digunakan bersama tools Python seperti pandas dan matplotlib.

# AI Support Explanation
Penggunaan IBM Granite digunakan untuk :
- Mengklasifikasikan tren penggunaan obat (meningkat, menurun, stabil, atau fluktuatif).
- Membuat ringkasan otomatis berdasarkan pola data.
- Memberikan rekomendasi umum berdasarkan pola tren yang ditemukan.

