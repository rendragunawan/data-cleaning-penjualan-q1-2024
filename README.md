# 🧼 Data Cleaning Penjualan Q1 2024

Proyek ini merupakan bagian dari latihan portofolio sebagai calon data analyst. Dataset yang digunakan adalah data penjualan triwulan pertama 2024 (Q1), dan proyek ini berfokus pada proses pembersihan data menggunakan Python dan Pandas di Jupyter Notebook.

## 🎯 Tujuan
- Membersihkan dataset mentah dari masalah umum seperti format tanggal tidak seragam, data duplikat, dan nilai kosong.
- Menyiapkan dataset agar dapat digunakan untuk analisis lanjutan (visualisasi, prediksi, dll).

## 📁 Struktur File
| File                          | Deskripsi                                      |
|------------------------------|------------------------------------------------|
| `dataset_penjualan_kotor.csv` | Dataset mentah sebelum dibersihkan             |
| `dataset_penjualan_bersih.csv`| Dataset yang telah dibersihkan menggunakan Pandas |
| `data-cleaning-penjualan.ipynb` | Notebook proses cleaning data langkah demi langkah |

## 🔧 Proses Cleaning
- Format tanggal diseragamkan ke `YYYY-MM-DD`
- Nama produk diubah menjadi lowercase
- Nilai kosong di kolom `Jumlah` dan `Harga Satuan` diisi dengan `0`
- Baris duplikat dihapus
- Dataset hasil dibersihkan dan disimpan sebagai `.csv`

## 📚 Tools yang Digunakan
- Python
- Pandas
- Jupyter Notebook

## ✍️ Catatan
Proyek ini merupakan bagian dari proses belajar dengan pendekatan _learn by doing_, bertujuan untuk memperkuat pemahaman dasar data cleaning yang sering ditemui oleh seorang data analyst.

