# Streamer Game Data Preprocessing - UTS

Repositori ini berisi proyek analisis dan pra-pemrosesan data untuk dataset **32_Streamer_Game.csv**. Proyek ini dikembangkan sebagai bagian dari tugas Ujian Tengah Semester (UTS) untuk mendemonstrasikan alur kerja *data cleaning* dan *feature engineering* sebelum tahap pemodelan machine learning.

## 📌 Deskripsi Proyek
Proyek ini berfokus pada pengolahan dataset performa streamer game. Tantangan utama dalam data ini adalah adanya data kategorikal pada jenis platform serta rentang nilai yang sangat bervariasi pada metrik penonton dan donasi.

**Tahapan Utama:**
1. **Data Cleaning:** Identifikasi dan penanganan nilai kosong (*missing values*) atau data yang tidak konsisten.
2. **Data Encoding:** Mengubah fitur kategorikal `Platform_Type` menjadi format numerik menggunakan teknik *One-Hot Encoding*.
3. **Data Scaling & Standardization:** Melakukan penskalaan pada fitur numerik (seperti `Avg_Viewers`, `Donation_Amount`, dan `Hours_Streamed`) agar model tidak bias terhadap variabel dengan skala besar.

## 🛠️ Teknologi yang Digunakan
* **Bahasa:** Python 3.x
* **Library Utama:**
  * `Pandas`: Manipulasi dan analisis data tabel.
  * `NumPy`: Komputasi numerik.
  * `Scikit-Learn`: Implementasi *Encoder* dan *Scaler*.
  * `Matplotlib/Seaborn` (Opsional): Visualisasi data.
* **Tools:** VS Code.

## 📂 Struktur File
* `UTS.ipynb`: Notebook utama yang berisi kode implementasi dan penjelasan.
* `32_Streamer_Game.csv`: Dataset mentah yang digunakan dalam proyek.
* `LaporanUTS_245314114.pdf`: Dokumentasi tertulis mengenai hasil analisis dan kesimpulan.

## 🚀 Cara Menjalankan
1. Clone repository ini:
   ```bash
   git clone [https://github.com/username-kamu/Streamer-Data-Preprocessing-UTS.git](https://github.com/username-kamu/Streamer-Data-Preprocessing-UTS.git)