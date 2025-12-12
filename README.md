# Cafe Sales Analysis & Prediction (UAS Data Science)


> **Final Semester Project** | **Mata Kuliah: Data Science**

> **Dataset:** [Dirty Cafe Sales (Kaggle)](https://www.kaggle.com/code/parthpatil256/dirty-cafe-sales)


Repository ini berisi dokumentasi teknis dan kode Python untuk menyelesaikan tugas akhir semester. Fokus utama proyek ini adalah mempraktikkan siklus **CRISP-DM**, mulai dari pembersihan data yang sangat kotor hingga pembuatan model prediksi.


## Tujuan Pembelajaran

* Menggunakan metode **CRISP-DM** selama proses pengerjaan data science. 


## Alur Pengerjaan

1.  **Bisnis Understanding:** Memahami tujuan bisnis, mengumpulkan pertanyaan dari masalah bisnis yang ada.

2.  **Data Understanding:** Mengidentifikasi anomali (kolom angka berisi teks "ERROR/UNKNOWN").

3.  **Data Preparation:** 

    * *Forced Conversion* ke numerik.

    * Imputasi nilai kosong pada kategori.

    * Validasi integritas data (`Quantity` * `Price` vs `Total Spent`).

5.  **Modeling:** Uji coba Linear Regression, Ridge, Lasso, dan Decision Tree.

6.  **Evaluation:** Melihat apakah model sudah menjawab pertanyaan bisnis atau belum.

7.  **Deployment:** Model Siap diimplementasikan ke produk.


## Hasil Evaluasi (Key Result)


Model **Linear Regression** terpilih sebagai model terbaik dengan performa paling stabil untuk generalisasi.


| Metric | Linear Regression | Decision Tree* |

| :--- | :--- | :--- |

| **MAE** | 0.05 | 0.00 |

| **MSE** | 0.01 | 0.00 |

| **R² Score** | **0.91** | 1.00 |


*> Catatan: Skor R² 1.00 pada Decision Tree diindikasikan sebagai overfitting pada data latih ini.*


## File Project

* `code/UAS_DataScience.ipynb`: **Kode Analisis Lengkap (End-to-End)**.

* `dataset/dirty_cafe_sales.csv`: Dataset asli (kotor).

---

*Disclaimer: Proyek ini dibuat untuk tujuan akademik dan edukasi menggunakan dataset publik.*


