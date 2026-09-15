# Machine Learning - Clustering & Classification Project Michael Joshua Zhang

Dokumen ini berisi proyek analisis data dan pemodelan Machine Learning menggunakan teknik **Clustering** (Pengelompokan) dan **Classification** (Klasifikasi) sebagai bagian dari modul pembelajaran Machine Learning dari Dicoding.

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data melalui dua pendekatan utama Unsupervised dan Supervised Learning:
1. **Clustering**: Mengelompokkan data berdasarkan kemiripan karakteristik tanpa label terdefinisi.
2. **Klasifikasi**: Membangun model prediktif untuk mengkategorikan data ke dalam kelas/label target tertentu.

## 📁 Struktur Berkas
- `*.ipynb` / `*.py` : Berkas kode pemrograman (Jupyter Notebook / Python script) yang berisi pemrosesan data, eksperimen model clustering, serta pelatihan model klasifikasi.
- `dataset/` : Berkas data yang digunakan dalam proses clustering dan klasifikasi.
- `results/` / `visualizations/` : Grafik hasil pengelompokan cluster, matriks evaluasi klasifikasi (confusion matrix), dan metrik kinerja model.

## 🚀 Algoritma & Evaluasi

### 1. Clustering (Unsupervised Learning)
- **Algoritma**: K-Means Clustering (atau algoritma lain yang digunakan)
- **Evaluasi**: 
  - *Elbow Method* (menentukan jumlah cluster optimal $K$)
  - *Silhouette Score* (mengukur kualitas pemisahan cluster)

### 2. Klasifikasi (Supervised Learning)
- **Algoritma**: Random Forest, Decision Tree, Logistic Regression, atau Support Vector Machine (SVM)
- **Evaluasi**: 
  - *Accuracy, Precision, Recall, F1-Score*
  - *Confusion Matrix*

## 🛠️ Modul & Pustaka Utama
- Python 3.x
- Pandas & NumPy (Manipulasi & Pemrosesan Data)
- Scikit-Learn (Pemodelan Machine Learning & Evaluasi)
- Matplotlib & Seaborn (Visualisasi Data & Hasil Model)

---
*Catatan: File ini disusun sebagai bagian dari alur belajar Machine Learning.*
