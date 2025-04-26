# Amazon Valentine Dashboard 2024

Repositori ini berisi hasil analisis dan visualisasi data dari daftar **Amazon Best Sellers Top Valentine Gifts 2024**. Proyek ini mencakup proses pembersihan data (*data cleansing*) dan pembuatan dashboard interaktif menggunakan Tableau untuk memberikan wawasan yang dapat digunakan.

## Daftar Isi
- [Tentang Proyek](#tentang-proyek)
- [Tujuan](#tujuan)
- [Tahapan Proyek](#tahapan-proyek)
  - [Data Cleansing](#data-cleansing)
  - [Dashboard Tableau](#dashboard-tableau)
- [Cara Mengakses Dashboard](#cara-mengakses-dashboard)
- [Struktur Direktori](#struktur-direktori)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)

## Tentang Proyek

Proyek ini bertujuan untuk menganalisis daftar produk "Valentine's Best Sellers" di Amazon pada tahun 2024. Data yang digunakan telah melewati proses pembersihan untuk memastikan kualitas dan keakuratan analisis.

## Tujuan

1. Membersihkan data mentah untuk menghilangkan duplikasi, nilai kosong, dan inkonsistensi.
2. Membuat dashboard interaktif menggunakan Tableau untuk memberikan wawasan tentang produk terbaik untuk Hari Valentine 2024.

## Tahapan Proyek

### Data Cleansing
Tahapan ini melibatkan:
- Menghapus data duplikat dan menangani nilai kosong.
- Memastikan konsistensi format untuk semua kolom.
- Melakukan transformasi data agar siap digunakan dalam analisis.

### Dashboard Tableau
Hasil pembersihan data digunakan untuk membuat dashboard interaktif menggunakan Tableau. Dashboard ini berisi visualisasi seperti:
- Produk terbaik berdasarkan kategori.
- Tren harga produk.
- Peringkat penjualan dan ulasan konsumen.

## Cara Mengakses Dashboard

Anda dapat mengakses dashboard Tableau secara publik melalui tautan berikut:
[Dashboard Tableau - Amazon Valentine's Best Sellers 2024](https://public.tableau.com/app/profile/muhammad.hanif.al.azis/viz/amazon_2024_valentines_best_sellers/Dashboard1)

## Struktur Direktori

Berikut adalah struktur direktori proyek:
```
Amazon-Valentine-Dashboard-2024/
│
├── data/
│   ├── raw_data.csv           # Data mentah sebelum pembersihan
│   ├── cleaned_data.csv       # Data yang telah dibersihkan
│
├── notebooks/
│   ├── data_cleaning.ipynb    # Notebook untuk proses pembersihan data
│
├── tableau/
│   ├── dashboard.twbx         # File Tableau Workbook
│
└── README.md
```

## Teknologi yang Digunakan

- **Bahasa Pemrograman**: Python
- **Framework/Library**:
  - *Data Manipulation*: `pandas`
  - *Visualization*: Tableau Public
