# Klasifikasi Bunga Iris dengan K-Nearest Neighbors (KNN)

Proyek ini bertujuan untuk mengklasifikasikan jenis bunga Iris berdasarkan ukuran kelopak dan mahkota menggunakan algoritma **K-Nearest Neighbors (KNN)**.

## 📌 Dataset

- Dataset yang digunakan: **Iris Dataset**
- Fitur yang digunakan:
  - `sepal length (cm)`
  - `sepal width (cm)`
  - `petal length (cm)`
  - `petal width (cm)`
- Label kelas:
  - **Setosa** (0)
  - **Versicolor** (1)
  - **Virginica** (2)

## 🔧 Teknologi yang Digunakan

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib & Seaborn

## 📊 Hasil Evaluasi Model

- Akurasi model: **97%** ✅
- **Classification Report**:
  - Precision, Recall, dan F1-score tinggi untuk setiap kelas
- **Confusion Matrix**:
  - Sebagian besar prediksi benar
- **PCA Visualization**:
  - Pemisahan kelas terlihat jelas dengan Principal Component Analysis (PCA)

## 🚀 Cara Menjalankan Proyek

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/repository.git
   ```
2. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook Jupyter:
   ```bash
   jupyter notebook Iris_Knn_Classification.ipynb
   ```

## 📂 Struktur Proyek

```
│── Iris_Knn_Classification.ipynb   # Notebook utama
│── README.md                        # Dokumentasi proyek
│── requirements.txt                  # Daftar dependensi
│── dataset/                          # Folder dataset (jika ada)
```

## 📌 Catatan Tambahan

- Model menggunakan **GridSearchCV** untuk mencari nilai K terbaik
- **Cross-validation (CV=10)** digunakan untuk meningkatkan stabilitas model
- **PCA digunakan untuk visualisasi data dalam 2D**
