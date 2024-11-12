# Analisis Data Bike Sharing Menggunakan Streamlit

Analisis Bike Sharing Dataset menggunakan Python dan Streamlit.

## Fitur

Aplikasi ini dibagi menjadi dua tab:
1. **Rental Sepeda**: Menampilkan data umum, pengguna sepeda per tanggal tertentu, dan ketentuan musim.
2. **Analisis Data**: Melakukan analisis statistik seperti outlier dan perbandingan jumlah penyewa sepeda berdasarkan musim dan kondisi cuaca.

## Dataset

Dataset yang digunakan adalah Bike Sharing Dataset yang dapat ditemukan di Kaggle.

## Struktur Kode

1. **Data Load**: Dataset *hour.csv* dimuat menggunakan `pandas` dan dikonversi ke format *datetime*.
2. **Tab Rental Sepeda**:
   - Menampilkan deskripsi umum dari dataset.
   - Filter data penyewaan sepeda berdasarkan tanggal.
   - Menyediakan informasi tentang ketentuan musim.
3. **Tab Analisis Data**:
   - Analisis outlier pada jumlah penyewa menggunakan grafik *boxplot*.
   - Membandingkan jumlah penyewa sepeda berdasarkan musim dan kondisi cuaca.

### Struktur Dataset

- **dteday**: Tanggal penyewaan sepeda
- **cnt**: Jumlah penyewa sepeda
- **Musim dan Kondisi Cuaca**: Variabel musim dan kondisi cuaca untuk analisis lebih lanjut

## Instalasi

pip install pandas streamlit matplotlib seaborn numpy

## Run steamlit app
streamlit run main.py
