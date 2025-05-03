# Stock-Price-Forecasting-MSFT-vs-NVDA-2024-2025-
eksplorasi data historis harga saham Microsoft (MSFT) dan Nvidia (NVDA), serta membangun model prediksi harga saham menggunakan algoritma Linear Regression. Data diambil dari Yahoo Finance untuk rentang waktu 21 Maret 2024 – 21 Maret 2025.

🧰 Tools & Library
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- yfinance

📁 Struktur Folder
📦root/
 ┣ 📄 MSFT_cleaned.csv
 ┣ 📄 NVDA_cleaned.csv
 ┣ 📄 stock_forecasting.ipynb
 ┗ 📄 README.md
 
🔍 Tahapan Proyek
Data Collection
- Menggunakan yfinance untuk mengunduh data historis saham.
- Preprocessing
- Rename kolom agar lebih readable
- Cek & handle missing values
- Normalisasi fitur numerik
- Exploratory Data Analysis (EDA)
- Visualisasi tren harga
- Korelasi fitur
- Train-Test Split (80:20)
- Modeling
- Linear Regression

📈 Hasil Evaluasi Model
Metrik	MSFT	NVDA
MAE	0.0573	0.0559
MSE	0.0067	0.0060
RMSE	0.0817	0.0777
R² Score	0.8495	0.7023

📌 Kesimpulan: Model Linear Regression bekerja lebih baik untuk saham MSFT dibanding NVDA, berdasarkan nilai R² yang lebih tinggi dan performa keseluruhan.
