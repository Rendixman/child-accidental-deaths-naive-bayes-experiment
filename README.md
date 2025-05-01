
#  child-accidental-deaths-Naive Bayes Experiment

Proyek ini adalah eksperimen klasifikasi menggunakan algoritma **Naive Bayes** untuk memprediksi apakah suatu kejadian menghasilkan korban luka berdasarkan dataset kecelakaan anak-anak. Eksperimen ini mencakup preprocessing data, pelatihan model, evaluasi performa, dan visualisasi hasil.

## Dataset
Dataset yang digunakan mencakup informasi tentang jumlah korban luka dan korban meninggal dalam kecelakaan. Fitur yang digunakan meliputi:
- **State**: Negara bagian tempat kecelakaan terjadi.
- **# Killed**: Jumlah korban meninggal.
- **# Injured**: Jumlah korban luka (target klasifikasi).

## Tujuan
- Membuat model klasifikasi untuk memprediksi apakah ada korban luka berdasarkan informasi pada dataset.
- Mengevaluasi performa model menggunakan **Confusion Matrix**.

## Teknologi yang Digunakan
- **Python**: Bahasa pemrograman utama.
- **Pandas**: Untuk manipulasi data.
- **Scikit-learn**: Untuk implementasi algoritma Naive Bayes dan evaluasi model.
- **Matplotlib**: Untuk visualisasi hasil evaluasi (Confusion Matrix).

## Struktur Proyek
- `accidental_deaths_children.csv`: Dataset asli yang digunakan dalam eksperimen.
- `Child_accidental_deaths_analysis.ipynb`: Notebook Jupyter berisi kode eksperimen dan analisis.
- `README.md`: Dokumentasi proyek.

## Cara Menjalankan Proyek
1. **Clone Repository**:
   ```bash
   git clone https://github.com/username/naive-bayes-experiment.git
