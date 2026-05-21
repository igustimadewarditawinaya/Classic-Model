# 📊 Classic Model Sales Dashboard Analysis

## 📌 Deskripsi Project
Project ini merupakan dashboard analisis penjualan menggunakan **Power BI** dengan dataset **Classic Model Sales**. Dashboard dirancang untuk membantu memantau performa penjualan dan profit perusahaan melalui visualisasi interaktif dan KPI bisnis.

Dashboard menampilkan:
- Monthly Sales Trend
- Month-over-Month (% Change)
- Total Sales
- Net Profit
- Toggle button untuk berpindah antara tampilan Sales dan Net Profit
- Visualisasi interaktif menggunakan berbagai chart

Project ini bertujuan untuk membantu stakeholder memahami performa bisnis, tren penjualan, profitabilitas, serta perilaku pelanggan berdasarkan data historis penjualan.

---

# 📷 Dashboard Preview

## Sales Overview - Page 1

![Sales Overview Page 1](Dashboard/Sales_Overview-Page1.png)

---

## Sales Overview - Page 2

![Sales Overview Page 2](Dashboard/Sales_Overview-Page2.png)

---

## 🎯 Tujuan Project
- Memonitor performa penjualan bulanan perusahaan.
- Menganalisis perubahan penjualan dari bulan ke bulan (MoM Change).
- Mengidentifikasi produk dan product line dengan kontribusi tertinggi.
- Menganalisis profitabilitas berdasarkan customer dan wilayah.
- Membantu pengambilan keputusan bisnis berbasis data.

---

## 🗂️ Dataset Information

Dataset terdiri dari beberapa kolom utama:

| Kolom | Deskripsi |
|---|---|
| orderDate | Tanggal pemesanan |
| orderNumber | Nomor order |
| productName | Nama produk |
| productLine | Kategori produk |
| customerName | Nama customer |
| customer_country | Negara customer |
| office_country | Negara kantor/office |
| buyPrice | Harga beli produk |
| priceEach | Harga jual per unit |
| quantityOrdered | Jumlah produk yang dipesan |
| sales_value | Total nilai penjualan |
| cost_of_sales | Total biaya penjualan |

---

## 🛠️ Tools & Technologies
- Power BI
- SQL / MySQL
- Power Query
- DAX (Data Analysis Expressions)

---

## 📈 Dashboard Features

### ✅ KPI Cards
Dashboard menampilkan KPI utama seperti:
- Total Sales
- Net Profit
- Monthly Sales
- MoM % Change

---

### ✅ Interactive Button
Terdapat tombol interaktif untuk:
- Switch antara tampilan **Sales**
- dan **Net Profit**

Hal ini membantu pengguna melakukan analisis secara lebih fleksibel dalam satu dashboard.

---

## 📊 Visualisasi yang Digunakan

| Visual | Fungsi |
|---|---|
| KPI Chart | Menampilkan metrik utama bisnis |
| Line Chart | Analisis tren penjualan bulanan |
| Column Chart | Perbandingan sales antar kategori |
| Donut Chart | Distribusi kontribusi product line |
| Bar Chart | Perbandingan performa customer/negara |
| Scatter Plot | Analisis hubungan sales dan profit |

---

# 📌 Business Insight & Data Analyst Analysis

## 1. Tren Penjualan Bulanan
Analisis line chart menunjukkan bahwa penjualan mengalami fluktuasi setiap bulan. Beberapa periode menunjukkan peningkatan sales yang signifikan, sedangkan pada periode lain terjadi penurunan performa.

### Insight Data Analyst:
- Pola ini mengindikasikan adanya seasonal demand pada produk tertentu.
- Peningkatan penjualan kemungkinan dipengaruhi oleh momentum bisnis seperti akhir tahun, promo, atau peningkatan permintaan pasar.
- Penurunan sales dapat dijadikan indikator untuk evaluasi strategi marketing maupun inventory management.

### Rekomendasi:
- Menyiapkan stok lebih besar pada periode peak season.
- Membuat strategi promosi pada bulan dengan penjualan rendah.
- Menggunakan forecasting untuk prediksi sales berikutnya.

---

## 2. Product Line dengan Kontribusi Sales Tertinggi
Berdasarkan visualisasi donut chart dan column chart, terdapat beberapa product line yang mendominasi total sales perusahaan.

### Insight Data Analyst:
- Tidak semua kategori produk memiliki kontribusi yang seimbang.
- Product line tertentu menjadi driver utama revenue perusahaan.
- Ketergantungan terhadap satu kategori produk dapat menjadi risiko bisnis apabila demand menurun.

### Rekomendasi:
- Fokus meningkatkan retention dan marketing pada kategori dengan performa tinggi.
- Melakukan evaluasi terhadap product line dengan sales rendah.
- Diversifikasi produk untuk mengurangi ketergantungan pada satu kategori utama.

---

## 3. Analisis Net Profit dan Margin
Dashboard menunjukkan bahwa sales tinggi tidak selalu menghasilkan profit tinggi. Hal ini dipengaruhi oleh:
- cost of sales,
- margin produk,
- quantity ordered.

### Insight Data Analyst:
- Beberapa produk menghasilkan revenue besar namun margin profit rendah.
- Terdapat kemungkinan biaya operasional atau biaya pembelian produk terlalu tinggi.
- Profitability analysis menjadi lebih penting dibanding hanya melihat sales volume.

### Rekomendasi:
- Mengoptimalkan pricing strategy.
- Fokus pada produk dengan margin profit tinggi.
- Melakukan efisiensi cost untuk meningkatkan net profit.

---

## 4. Customer dengan Kontribusi Tertinggi
Bar chart menunjukkan beberapa customer memiliki kontribusi transaksi jauh lebih besar dibanding customer lainnya.

### Insight Data Analyst:
- Sebagian besar revenue kemungkinan berasal dari small group of customers (Pareto Principle / 80-20 Rule).
- Kehilangan customer utama dapat berdampak besar terhadap revenue perusahaan.

### Rekomendasi:
- Membuat loyalty program untuk high-value customers.
- Meningkatkan customer relationship management (CRM).
- Mengembangkan strategi untuk meningkatkan kontribusi customer lain.

---

## 5. Analisis Berdasarkan Negara
Visualisasi menunjukkan adanya perbedaan performa sales antar negara.

### Insight Data Analyst:
- Negara tertentu menjadi market utama perusahaan.
- Beberapa negara memiliki sales rendah namun masih memiliki potensi pertumbuhan.

### Rekomendasi:
- Fokus ekspansi pada market dengan pertumbuhan tinggi.
- Mengevaluasi strategi distribusi dan marketing pada negara dengan performa rendah.
- Menyesuaikan strategi bisnis berdasarkan karakteristik regional market.

---

## 6. Hubungan Quantity Ordered dan Sales
Scatter plot menunjukkan hubungan positif antara jumlah order dan nilai sales.

### Insight Data Analyst:
- Semakin besar quantity ordered, semakin besar sales yang dihasilkan.
- Namun terdapat transaksi quantity kecil dengan profit tinggi, yang menunjukkan adanya produk premium atau margin tinggi.

### Rekomendasi:
- Mengidentifikasi produk dengan high-margin performance.
- Mengembangkan strategi upselling dan bundling.
- Meningkatkan penjualan produk premium.

---

## 7. Efektivitas Dashboard untuk Business Monitoring
Dashboard memungkinkan stakeholder memonitor KPI secara real-time dan interaktif.

### Insight Data Analyst:
- Dashboard membantu mempercepat proses pengambilan keputusan.
- Visualisasi interaktif memudahkan identifikasi masalah bisnis dan peluang pertumbuhan.
- KPI monitoring membantu perusahaan lebih data-driven.

### Business Value:
- Faster decision making
- Better performance monitoring
- Improved business strategy
- Easier identification of trends and anomalies

---

# 📌 Kesimpulan
Dashboard ini membantu proses monitoring performa bisnis secara interaktif dan real-time melalui visualisasi data yang informatif.

Melalui dashboard ini, stakeholder dapat:
- memahami tren penjualan,
- mengevaluasi profitabilitas,
- mengidentifikasi product line terbaik,
- menganalisis customer behavior,
- serta mengambil keputusan bisnis berbasis data dengan lebih efektif.

Project ini juga menunjukkan kemampuan dalam:
- data visualization,
- dashboard development,
- KPI analysis,
- business intelligence,
- serta data storytelling menggunakan Power BI.

---

# 📂 Struktur Project

```bash
Classic-Model/
│
├── dataset/
│   ├── classic_model_sales.csv
│
├── Dashboard/
│   ├── Sales_Overview-Page1.png
│   ├── Sales_Overview-Page2.png
│
├── dashboard/
│   ├── classic_model_dashboard.pbix
│
├── README.md
