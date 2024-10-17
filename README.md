# Prediksi Conversion Report Digital Marketing💡 - ![XGBoost](https://img.shields.io/badge/XGBoost-00B140?style=for-the-badge&logo=XGBoost&logoColor=white)

Repositori ini berisi project prediksi konversi menggunakan beberapa model (KNN, SVM, Decision Tree, Random Forest, XGBoost) klasifikasi dengan base parameter, lalu model terbaik selanjutnya dilakukan hyperparameter tuning, hasilnya model ini menggunakan **XGBoost** sebagai model prediksi. Project ini bertujuan untuk menerapkan model machine learning untuk memprediksi konversi berdasarkan dataset yang tersedia. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga percobaan model menggunakan unseen data.

## Daftar Isi 🗒️
1. [Link Terkait Project](#link-terkait-project-)
2. [Project Overview](#project-overview-)
3. [Metode yang Digunakan](#metode-yang-digunakan-)
4. [File yang Tersedia](#file-yang-tersedia-)
5. [Cara Menggunakan Project Ini](#cara-menggunakan-project-ini-)
6. [Dependencies](#dependencies-)
7. [Libraries](#libraries-)
8. [Author](#author-)

## Link Terkait Project ⛓️‍💥

- [Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-conversion-in-digital-marketing-dataset)
- [Deployment](https://huggingface.co/spaces/Ciputra/deployment)

## Project Overview 📝

Dalam proyek ini, saya menggunakan beberapa model klasifikasi dengan base parameter, lalu model terbaik selanjutnya dilakukan hyperparameter tuning untuk menganalisis data dan membangun model prediksi konversi. Beberapa langkah utama yang dicakup dalam proyek ini adalah:

1. **Import Libraries dan Eksplorasi Data**:
    - Memuat dataset dan melakukan eksplorasi awal untuk memahami struktur dan karakteristik data.

2. **Preprocessing Data**:
    - Melakukan pembersihan dan persiapan data, termasuk penanganan outlier dan imputasi nilai yang hilang.

3. **Pengembangan Model**:
    - Membangun dan melatih model lima model klasifikasi untuk memprediksi konversi.

4. **Evaluasi Model**:
    - Menggunakan metrik evaluasi untuk menilai kinerja model.

5. **Hyperparameter Tuning**:
   - Melakukan hyperparameter tuning menggunakan model terbaik.
     
7. **Evaluasi Model**:
   - Melakukan evaluasi terhadap model yang sudah dituning
     
9. **Pengambilan Keputusan untuk Model dan Bisnis**:
    - Mengambil keputusan terhadap model dan untuk bisnis

## Metode yang Digunakan 🛠️

- Statistik Inferensial
- Machine Learning
- Visualisasi Data
- Pemodelan Prediktif

## File yang Tersedia 📂

- `model_research.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, pengembangan model XGBoost, evaluasi model, dan wawasan yang diperoleh dari analisis.
- `data_inference.ipynb`: Jupyter Notebook yang berisi prediksi unseen data menggunakan model yang sudah dibuat sebelumnya
- `model.pkl, preproc.pkl`: Hasil penyimpanan model dan preprocessing
- `digital_marketing_campaign_dataset.csv`: Raw dataset
  
## Cara Menggunakan Project Ini 💻

1. Clone repositori ini ke dalam lokal Anda:
    ```bash
    git clone https://github.com/ciputrawangsa/Conversion-XGboost.git
    ```

2. Jalankan Jupyter Notebook untuk mengikuti alur analisis data:
    ```bash
    jupyter notebook model_research.ipynb
    ```

## Dependencies ⚙️

- ![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 3.10.14
- ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

## Libraries 📚
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Plotly
- Seadborn
- Matplotlib
- Imblearn
- Joblib

## Author ✍️
**Ciputra Wangsa**

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciputra-wangsa/)
