# 🍷 Wine Quality Classification

**Ujian Tengah Semester — Mata Kuliah Data Mining**

| | |
|---|---|
| **Nama** | Miftahudin |
| **NIM** | 2304020078 |
| **Dataset** | Wine Quality — fitur kimiawi anggur merah & putih |
| **Target** | `quality` — skor kualitas anggur skala **0–10** |
| **Tipe Masalah** | Klasifikasi Multi-kelas |

---

## 📋 Deskripsi

Proyek ini membangun model klasifikasi untuk memprediksi kualitas anggur berdasarkan fitur-fitur kimiawi seperti kadar alkohol, keasaman, sulfat, dan lainnya menggunakan algoritma Random Forest.

---

## 🔄 Alur Analisis

| No | Tahap | Keterangan |
|----|-------|-----------|
| 1 | **Import Library** | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| 2 | **Load Dataset** | Upload & load data training via Google Colab |
| 3 | **Preprocessing** | Penanganan missing values, duplikat, pisah fitur & target |
| 4 | **Feature Scaling** | StandardScaler — normalisasi skala antar fitur |
| 5 | **Train / Validation Split** | 80% training, 20% validasi (stratified) |
| 6 | **Modeling** | Random Forest Classifier |
| 7 | **Evaluasi** | Akurasi, Confusion Matrix, Classification Report |
| 8 | **Simpan Model** | Export model & scaler ke file `.pkl` |
| 9 | **Prediksi** | Load model → prediksi data testing |
| 10 | **Simpan Hasil** | Export hasil prediksi ke CSV |

---

## 🤖 Model

| Model | Keterangan |
|-------|-----------|
| **Random Forest** ✅ | Ensemble 200 pohon, `class_weight=balanced` |

---

## 📊 Hasil Prediksi

| Quality | Jumlah Data |
|---------|------------|
| 5 | 137 |
| 6 | 123 |
| 7 | 26 |
| **Total** | **286** |

---

## 📁 File

| File | Keterangan |
|------|-----------|
| `UTS.ipynb` | Notebook utama — analisis lengkap dengan interpretasi setiap langkah |
| `hasilprediksi_078.csv` | Hasil prediksi data testing (kolom: `Id`, `Quality`) |

---
