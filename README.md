# 🧾 Sales Data Analysis Project

Proyek ini merupakan hasil eksplorasi dan analisis data penjualan menggunakan **Python** dengan memanfaatkan dataset `Sales.csv`. Analisis dilakukan untuk memahami pola penjualan, profitabilitas produk, tren musiman, serta hubungan antar variabel keuangan. Proyek ini juga mengikuti tahapan kerja analitik yang diajarkan dalam **Google Data Analytics Course**.

## 📂 Dataset  

Dataset yang digunakan bernama **Europe Bike Store Sales** dan berasal dari **Kaggle**.  
Dataset ini berisi data transaksi penjualan yang mencakup informasi seperti tanggal pemesanan, kategori produk, jumlah barang yang dibeli, harga satuan, total pendapatan (revenue), dan keuntungan (profit).  
Data ini merepresentasikan aktivitas penjualan dari beberapa kategori produk utama, yaitu **Bikes**, **Clothing**, dan **Accessories**.  
Setiap baris dalam dataset menunjukkan satu transaksi penjualan, yang dapat digunakan untuk menganalisis performa bisnis, efisiensi harga, serta tren musiman penjualan.

---

## 📁 Struktur Proyek
├── Sales.csv # Dataset penjualan utama
├── analysis.ipynb # Notebook utama berisi proses analisis & visualisasi
└── README.md # Dokumentasi proyek


---

## 🧰 Teknologi yang Digunakan
- **Python 3.x**
- **Pandas** → pengolahan dan analisis data  
- **Matplotlib** & **Seaborn** → visualisasi data  

---

## 📊 Alur Pengerjaan Proyek

Proyek ini disusun mengikuti tahapan analisis data profesional, yaitu:

### 1️⃣ Asking
Menentukan pertanyaan utama yang ingin dijawab melalui data:
- Negara atau wilayah mana yang menghasilkan revenue tertinggi?
- Produk apa yang paling menguntungkan?
- Apakah ada pola musiman dalam penjualan?
- Bagaimana hubungan antara harga, jumlah pesanan, dan profit?

---

### 2️⃣ Prepare
Menyiapkan dataset `Sales.csv` untuk analisis:
- Menghapus data kosong (jika ada)  
- Mengubah kolom tanggal ke format `datetime`  
- Membuat kolom tambahan seperti `Year`, `Month`, dan `Profit_Margin`  

---

### 3️⃣ Process
Menggunakan *pandas* untuk transformasi dan perhitungan:
- `groupby()` untuk agregasi berdasarkan negara, produk, dan waktu  
- Menghitung metrik seperti `Revenue`, `Profit`, dan `Profit_Margin`  
- Menyusun data untuk visualisasi tren dan distribusi  

---

### 4️⃣ Analyze
Analisis utama dan tambahan dilakukan meliputi:

#### 🔹 Analisis Utama
- **Top 10 Negara berdasarkan Revenue & Profit**  
  → Mengidentifikasi wilayah dengan kontribusi penjualan terbesar.  
- **Distribusi Revenue berdasarkan Kategori Produk**  
  → Mengetahui kategori produk yang mendominasi penjualan.  
- **Tren Revenue Tahunan**  
  → Melihat pertumbuhan dan fluktuasi penjualan antar tahun.  
- **Perbandingan Revenue berdasarkan Gender & Age Group**  
  → Analisis segmentasi pelanggan.  

#### 🔹 Analisis Tambahan
1. **Korelasi Antar Variabel Keuangan**  
   Menunjukkan hubungan antara *Revenue*, *Profit*, *Cost*, dan *Order Quantity*.  
   Hasil: hubungan sangat kuat antara *Revenue* dan *Profit*, sementara *Order Quantity* memiliki korelasi negatif ringan.

2. **Analisis Musiman Penjualan (Revenue per Bulan)**  
   Menggambarkan pola penjualan rata-rata per bulan.  
   Hasil: penjualan meningkat tajam menjelang pertengahan dan akhir tahun, menunjukkan pola musiman yang kuat.

3. **Profit Margin per Kategori Produk**  
   Mengukur efisiensi keuntungan per kategori.  
   Hasil: kategori *Accessories* memiliki margin tertinggi (~57%), diikuti *Bikes* (~33%) dan *Clothing* (~31%).

4. **Efektivitas Harga terhadap Kuantitas Terjual**  
   Menggambarkan hubungan harga satuan dan volume penjualan.  
   Hasil: korelasi negatif — semakin tinggi harga, semakin rendah jumlah produk yang dibeli.

---

### 5️⃣ Visualize
Visualisasi dilakukan menggunakan **Matplotlib** dan **Seaborn**, dengan grafik seperti:
- **Bar Chart** → Perbandingan antar kategori dan negara  
- **Line Chart** → Tren musiman revenue  
- **Heatmap** → Korelasi antar variabel keuangan  
- **Scatter Plot** → Hubungan harga dan kuantitas  

Contoh hasil visualisasi:
- Korelasi antar variabel keuangan  
- Analisis musiman penjualan  
- Profit margin per kategori  
- Efektivitas harga terhadap kuantitas

---

### 6️⃣ Share
**Insight utama dari hasil analisis:**
- Revenue tinggi umumnya diikuti profit besar, tapi perlu kontrol cost untuk efisiensi.  
- Produk *Accessories* paling menguntungkan dan efisien secara margin.  
- Pola musiman menunjukkan puncak penjualan pertengahan dan akhir tahun.  
- Harga berpengaruh negatif terhadap kuantitas — perlu strategi harga yang tepat untuk menjaga volume penjualan.  

---

## 💡 Kesimpulan
Analisis ini memberikan gambaran komprehensif tentang kinerja penjualan berdasarkan data aktual.  
Hasilnya dapat digunakan untuk:
- Menentukan strategi harga dan promosi.  
- Memfokuskan penjualan pada produk ber-margin tinggi.  
- Merencanakan stok dan kampanye berdasarkan pola musiman.  

---

## 🧑‍💻 Pembuat
**Ardiansyah Ihsan Prakoso**  
📧 ihsanprakoso25@gmail.com 
💼 Data Analyst | Data Enthusiast  

---
