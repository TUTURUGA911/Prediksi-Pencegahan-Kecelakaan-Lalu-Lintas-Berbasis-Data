# 🚗 Traffic Accident Analysis & Driver Safety Recommendations

Proyek ini menganalisis dataset **US Accidents** dan memanfaatkan model **IBM Granite** melalui API Replicate untuk:
1. Melatih model prediksi tingkat keparahan kecelakaan.
2. Mengevaluasi performa model sebelum dan sesudah penyesuaian (Overfitting vs Penyesuaian).
3. Menghasilkan rekomendasi keselamatan berkendara untuk mengurangi risiko kecelakaan.

---

## 📦 Fitur Utama
- **Data Preprocessing**  
  Membersihkan dan mempersiapkan dataset `US_Accidents_March23.csv` untuk analisis.
- **Modeling**  
  Melatih model klasifikasi menggunakan scikit-learn.
- **Evaluasi Model**  
  Menampilkan Train Score, Test Score, Train Accuracy, dan Test Accuracy.
- **Visualisasi**  
  Menampilkan grafik performa model dan distribusi fitur.
- **IBM Granite Integration**  
  Menggunakan model `ibm-granite/granite-3.2-8b-instruct` untuk membuat rekomendasi keselamatan.
- **Output Rekomendasi**  
  Menyimpan 10 rekomendasi praktis untuk pengendara dalam file `.txt`.

---

## 🖥 Spesifikasi Proyek
- **Platform**: Google Colab (Python 3.10+)
- **Dataset**: US_Accidents_March23.csv (Sumber: Kaggle)
- **Bahasa Pemrograman**: Python
- **Library Utama**:
  - pandas == 2.2.2
  - numpy == 1.26.4
  - matplotlib == 3.9.0
  - seaborn == 0.13.2
  - scikit-learn == 1.5.0
  - langchain_community
  - replicate
- **Model AI**: ibm-granite/granite-3.2-8b-instruct (via Replicate API)
- **Kebutuhan API**: API Key Replicate
