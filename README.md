# 🤖 Klasifikasi Komentar Toxic di YouTube Menggunakan Machine Learning

Proyek ini merupakan tugas kelompok untuk mata kuliah **Machine Learning**. Sistem ini dirancang untuk mendeteksi dan mengklasifikasikan komentar netizen di platform YouTube menjadi dua kategori: **Toxic (1)** dan **Non-Toxic (0)** menggunakan pendekatan *Natural Language Processing* (NLP).

---

## 👥 Anggota Kelompok
* [2011102441211 / Ahmad Irham Dzulkifli]
* [2011102441026 / Ramayasin Gymnastiar]
* [2011102441133 / Tasya Putri Hardyani]

---

## 📊 Dataset & Preprocessing
* **Sumber Data:** Scraping mandiri pada konten video YouTube (Total: $\pm 1000$ komentar).
* **Fitur Labeling:** `0` (Non-Toxic) dan `1` (Toxic).
* **Tahapan Preprocessing:** * Case Folding
  * Cleansing (Regex untuk URL, Username, Angka, & Tanda Baca)
  * Stopwords Removal (Menggunakan Library Sastrawi)

---

## 🧠 Ekstraksi Fitur & Algoritma Model
* **Ekstraksi Fitur:** TF-IDF Vectorizer
* **Algoritma yang Digunakan:** 1. **Naive Bayes (MultinomialNB)**
  2. **Support Vector Machine (SVM)** -> *Model Terbaik*

### 📈 Hasil Evaluasi Perbandingan
* **Akurasi Naive Bayes:** 78.97%
* **Akurasi Support Vector Machine (SVM):** **83.64%**

---

## 🛠️ Tech Stack yang Digunakan
* **Language:** Python 3.x
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Scikit-Learn, Sastrawi, Matplotlib, Seaborn
