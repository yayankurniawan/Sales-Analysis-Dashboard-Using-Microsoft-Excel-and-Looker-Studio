# Sales Analysis Dashboard Using Microsoft Excel & Looker Studio

## Latar Belakang

Perusahaan ritel ini menjual produk dalam tiga kategori utama: Furniture, Office Supplies, dan Technology. Tim manajemen ingin mengetahui tren penjualan, profitabilitas, serta performa produk agar bisa mengambil keputusan strategis dalam hal promosi, distribusi, dan manajemen inventori.

## Tujuan Analisis
1. Berapa total sales, profit, quantity dan juga profit margin (sales/profit)?
2. Tren sales setiap bulan
3. Komposisi sales (penjualan) per segmen
4. Top 10 produk berdasarkan sales (penjualan)
5. Tampilkan tabel berupa produk kategori, product name, sales, profit, dan quantity
6. Tampilkan Filter bulan dan slicer berupa tanggal dan region

## Deskripsi Dataset 

Dataset ini berisi 9.994 baris transaksi penjualan dengan 21 kolom. Berikut penjelasan tiap kolom:

- Order ID :	ID unik untuk setiap order (satu order bisa punya beberapa produk).
- Order Date :	Tanggal order dilakukan.
- Ship Date :	Tanggal order dikirim.
- Ship Mode :	Metode pengiriman (Standard Class, Second Class, First Class, Same Day).
- Customer ID :	ID unik pelanggan.
- Customer Name :	Nama pelanggan.
- Segment :	Segmen pelanggan (Consumer, Corporate, Home Office).
- Country :	Negara pelanggan (semua data: United States).
- City :	Kota pelanggan.
- State :	Negara bagian (misal California, Texas, New York).
- Postal : Code	Kode pos pelanggan.
- Region :	Wilayah (Central, East, South, West).
- Product ID :	ID unik untuk setiap produk.
- Category :	Kategori utama produk (Furniture, Office Supplies, Technology).
- Sub-Category :	Sub-kategori produk (misal: Chairs, Phones, Binders, Storage, Tables).
- Product Name :	Nama lengkap produk.
- Sales :	Total nilai penjualan produk ($).
- Quantity :	Jumlah unit produk yang dijual.
- Discount :	Diskon yang diberikan (%).
- Profit :	Keuntungan bersih dari penjualan produk.
- Calendar :	Penanda waktu (mungkin bulan/tahun, tergantung dataset).

## Jawaban
### Berapa total sales, profit, quantity dan juga profit margin (sales/profit)?

<img width="398" height="86" alt="image" src="https://github.com/user-attachments/assets/bb10e553-8989-4327-98e2-3c5234c51ef9" />

### Tren sales setiap bulan

<img width="398" height="222" alt="image" src="https://github.com/user-attachments/assets/a76f5e21-3b5f-4d37-af60-374fc9db3630" />


Grafik:

<img width="1132" height="447" alt="image" src="https://github.com/user-attachments/assets/db70ee4c-bd2e-47df-a493-731d9fddddb8" />


### Komposisi sales (penjualan) per segmen

<img width="398" height="69" alt="image" src="https://github.com/user-attachments/assets/5b95c7ed-6488-4c45-87e4-fbea32aca9e0" />

Grafik:

<img width="649" height="448" alt="image" src="https://github.com/user-attachments/assets/60d0d3f7-21e4-4ca5-bbc6-a6765664804b" />

### Top 10 produk berdasarkan sales (penjualan)

<img width="672" height="188" alt="image" src="https://github.com/user-attachments/assets/45b7e5e5-a3e5-472d-ba03-40bc3e69cf09" />

Grafik:

<img width="1124" height="560" alt="image" src="https://github.com/user-attachments/assets/f0131fb0-a343-4346-9dfe-cddd356af325" />

### Tampilkan tabel berupa produk kategori, product name, sales, profit, dan quantity

<img width="921" height="358" alt="image" src="https://github.com/user-attachments/assets/f66c379f-4350-4945-b213-c09725e67e16" />

## Kesimpulan

### Metrik Utama
- Total Sales: $2,297,201

- Total Profit: $286,397

- Total Quantity Terjual: 37,873 unit

- Profit Margin: 12%
  
***Menunjukkan performa bisnis yang sehat, namun masih ada ruang untuk meningkatkan efisiensi dan margin keuntungan***

### Tren Penjualan Bulanan
- Penjualan tertinggi terjadi di November ($352,461) dan Desember ($325,294), menunjukkan lonjakan permintaan akhir tahun.

- Penjualan terendah di Februari ($59,751) dan Januari ($94,925), mengindikasikan perlunya strategi promosi di awal tahun.

- Lonjakan signifikan juga terjadi di Maret dan September, yang bisa dikaji lebih lanjut untuk peluang musiman.

### Komposisi Penjualan per Segmen
- Consumer: $1,161,401 (≈50.6%)

- Corporate: $706,146 (≈30.7%)

- Home Office: $429,653 (≈18.7%) ➡

***Segmen Consumer adalah pasar utama, sementara Corporate dan Home Office tetap relevan untuk strategi B2B dan produk profesional***

### Top 10 Produk Berdasarkan Penjualan
- Produk terlaris: Canon imageCLASS 2200 Advanced Copier dengan penjualan $61,600.

- Produk lainnya seperti binding machines, task chairs, dan videoconferencing units menunjukkan permintaan tinggi di segmen kantor.
  
## Dashboard

### Dashboard Microsoft Excel
			
<img width="1151" height="783" alt="image" src="https://github.com/user-attachments/assets/9d715ddf-d8d5-4868-a76a-979e3867607a" />

### Dashboard Looker Studio

![Sales_Analysis_page-0001](https://github.com/user-attachments/assets/3200f44f-df12-418a-88b1-274ed7193541)

Link Dashboard: https://lookerstudio.google.com/reporting/f41c835f-e068-4690-8a7c-8067b2dadd62

