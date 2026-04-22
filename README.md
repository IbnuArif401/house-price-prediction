# 🏠 House Price Prediction (Ames Housing Regression)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi harga jual rumah di Ames, Iowa, menggunakan algoritma **Linear Regression**. Fokus utamanya adalah memahami faktor-faktor fisik bangunan yang paling signifikan memengaruhi nilai pasar sebuah properti.

## 🛠️ Tech Stack
- **Bahasa:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Platform:** Kaggle

## 📊 Alur Kerja (Workflow)
1. **Exploratory Data Analysis (EDA):** Menganalisis korelasi antara fitur rumah dengan harga jual (`SalePrice`).
2. **Data Cleaning:** Menangani *missing values* pada fitur penting seperti `Lot Frontage` dan `Mas Vnr Area`.
3. **Feature Selection:** Menggunakan 5 fitur terkuat berdasarkan tingkat korelasi:
   - `Overall Qual` (Kualitas Material)
   - `Gr Liv Area` (Luas Lantai Atas)
   - `Garage Cars` (Kapasitas Garasi)
   - `Total Bsmt SF` (Luas Basemen)
   - `Full Bath` (Jumlah Kamar Mandi)
4. **Modeling:** Membangun model **Linear Regression** untuk memprediksi angka kontinu (harga).
5. **Evaluation:** Mengukur performa model menggunakan metrik *R-Squared* (R2) dan *Mean Absolute Error* (MAE).

## 📈 Hasil & Analisis
- **R2 Score:** **0.79** (Model mampu menjelaskan 79% variasi harga rumah).
- **Interpretasi:** Kualitas material bangunan (`Overall Qual`) merupakan faktor penentu harga yang paling dominan, diikuti oleh luas lantai bangunan.
- **Visualisasi:** Menyertakan grafik *Scatter Plot* yang menunjukkan kedekatan antara prediksi AI dengan harga asli di lapangan.

## 🚀 Cara Menjalankan
1. Clone repositori ini.
2. Buka file `.ipynb` di lingkungan Jupyter atau Google Colab.
3. Pastikan dataset `AmesHousing.csv` sudah tersedia di direktori yang sesuai.
