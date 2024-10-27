# Prediksi Conversion dari Report Digital Marketing💡 - ![XGBoost](https://img.shields.io/badge/XGBoost-00B140?style=for-the-badge&logo=XGBoost&logoColor=white)

Repositori ini berisi project prediksi konversi menggunakan beberapa model (KNN, SVM, Decision Tree, Random Forest, XGBoost) klasifikasi dengan base parameter, lalu model terbaik selanjutnya dilakukan hyperparameter tuning, hasilnya model ini menggunakan **XGBoost** sebagai model prediksi. Project ini bertujuan untuk menerapkan model machine learning untuk memprediksi konversi berdasarkan dataset yang tersedia. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga percobaan model menggunakan unseen data.

## Daftar Isi 🗒️
1. [Link Terkait Project](#link-terkait-project-)
2. [Project Overview](#project-overview-)
3. [Latar Belakang Masalah](#latar-belakang-masalah-)
4. [Problem Statement](#problem-statement-)
5. [Penjabaran Masalah](#penjabaran-masalah-)
6. [Metode yang Digunakan](#metode-yang-digunakan-)
7. [Kesimpulan Analisa](#kesimpulan-analisa)
8. [Test Unseen Data](#test-unseen-data-)
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

## Latar Belakang Masalah 🧐

PT ABC ingin meningkatkan conversion rate dan mendapatkan ROI yang lebih optimal dari kampanye digital mereka. Salah satu tantangan utama yang dihadapi perusahaan ini adalah memastikan bahwa iklan yang ditampilkan tepat sasaran dan menargetkan audiens yang memiliki potensi tinggi untuk melakukan konversi. Selain itu, PT ABC juga ingin memaksimalkan efektivitas re-targeting terhadap pelanggan yang sudah menunjukkan minat sebelumnya, namun belum melakukan pembelian. Dengan menggunakan data perilaku pelanggan yang telah ada, perusahaan berencana memanfaatkan machine learning untuk memprediksi apakah seorang pelanggan akan melakukan konversi atau tidak. Prediksi ini akan membantu PT ABC dalam mengembangkan strategi digital marketing yang lebih tepat, seperti personalisasi iklan, penawaran yang sesuai, dan memilih saluran kampanye yang efektif. Dengan demikian, PT ABC berharap dapat meningkatkan tingkat konversi dan mengoptimalkan ROI tanpa membuang sumber daya pada upaya pemasaran yang tidak efektif.

## Problem Statement √

**Specific:** PT ABC ingin meningkatkan conversion rate dan ROI kampanye digital marketing dengan menggunakan model klasifikasi machine learning untuk memprediksi apakah pelanggan akan melakukan konversi.

**Measurable:** Conversion rate meningkat sebesar 15% dan ROI meningkat sebesar 20% dalam 6 bulan, dengan akurasi prediksi konversi minimal 80%.

**Achievable:** Dengan data perilaku pelanggan yang tersedia, perusahaan mampu membangun model klasifikasi dan mengimplementasikannya ke dalam strategi pemasaran.

**Relevant**: Model prediksi klasifikasi cocok digunakan untuk memprediksi apakah seseorang akan melakukan conversion, setelah itu kita bisa menentukan langkah strategis dalam meningkatan conversion rate dan ROI sesuai dengan .

**Time-bound:** Tujuan ini akan dicapai dalam waktu 1 bulan setelah penerapan model machine learning.

**Problem statement:**
Meningkatkan conversion rate sebesar 15% dan ROI sebesar 20% PT ABC dalam 1 bulan dengan menggunakan model klasifikasi machine learning yang mampu memprediksi konversi pelanggan dengan akurasi minimal 80%.

## Penjabaran Masalah 📋

1. Apa yang bisa dilakukan untuk mengatasi permasalahan tersebut?
2. Model mana yang paling baik untuk mengatasi permasalahan yang ingin diselesaikan?

## Metode yang Digunakan 🛠️

- Statistik Inferensial
- Machine Learning
- Visualisasi Data
- Pemodelan Prediktif

## Kesimpulan Analisa 🧠

1. Berdasarkan hasil dari eksplorasi data, adapun hal yang bisa diimplementasikan dalam mencapai tujuan bisnis:
- Investasi lebih banyak pada channel referral dan PPC yang menunjukkan hasil terbaik. Pertimbangkan untuk meningkatkan anggaran atau strategi dalam kedua channel ini untuk memaksimalkan hasil konversi. Bisa menggunakan jasa influencer atau referal code untuk mendapatkan diskon. Bisa juga analisa hasil PPC dari campaign yang sudah dilakukan dan melakukan optimisasi.
- Tinjau kembali strategi pemasaran email. Mungkin perlu dilakukan segmentasi lebih baik atau pengujian konten untuk meningkatkan efektivitas karena adspendnya sedikit lebih tinggi dari channel SEO tetapi hasil conversionnya sedikit lebih kecil dari channel SEO.
- Dengan wanita menjadi demografis yang lebih cenderung melakukan konversi, bisa dipertimbangkan untuk mengembangkan kampanye yang secara khusus ditargetkan kepada wanita yang sudah terprediksi untuk melakukan conversion.
- Selain itu, bisa juga dipertimbangkan untuk menciptakan produk atau promosi yang lebih sesuai dengan preferensi usia di kategori muda yang terprediksi melakukan conversion.
- Karena pelanggan yang melakukan konversi memiliki waktu di situs yang lebih tinggi, upayakan untuk meningkatkan keterlibatan pengguna di situs Anda, mungkin melalui konten interaktif atau penawaran khusus. Agar customer yang terprediksi melakukan conversion atau tidak tetap dapat menikmati kenyamanan dalam eksplor website.
- Setelah mengetahui customer akan conert atau tidak, bisa disesuaikan dengan strategi per masing-masing tipe campaign agar bisa lebih maksimal

2. Model XGBoost yang dituning menunjukkan bahwa tuning berhasil meningkatkan kemampuan model dalam membedakan antara pelanggan yang akan melakukan konversi dan yang tidak. Sehingga selanjutnya dilakukan beberapa pendekatan dalam strategi bisnis untuk menciptakan dan meningkatkan conversion.

## Test Unseen Data 👀

**Berdasarkan output prediksi:**

Dari 10 data yang diberikan, 9 data diprediksi akan menghasilkan konversi (1), sementara 1 data diprediksi tidak akan menghasilkan konversi (0). Hal ini menunjukkan bahwa model cenderung memprediksi konversi lebih sering, yang mungkin dikarenakan model ini melakukan prediksi berdasarkan fitur dengan tepat yang mendukung tingkat konversi lebih tinggi.

**Analisa prediksi berdasarkan fitur yang digunakan:**

1 data diprediksi tidak akan menghasilkan konversi. Faktor-faktor yang mungkin berkontribusi terhadap prediksi ini:
- Ad Spend (Pengeluaran iklan) yang lebih rendah dibanding kampanye lain.
- Click-Through Rate (CTR) dan Conversion Rate yang lebih rendah.
- Engagement metrics, seperti Website Visits dan Pages Per Visit, juga lebih rendah.

9 data diprediksi akan menghasilkan conversion. Beberapa faktor yang mungkin mempengaruhi prediksi ini adalah:
- Click-Through Rate (CTR) yang lebih tinggi.
- Conversion Rate yang relatif lebih tinggi dibandingkan kampanye lain, seperti pada kampanye ID 7993 dan 7996.
- Waktu di Situs (Time On Site) yang tinggi, menunjukkan bahwa pengunjung lebih terlibat dengan konten situs.
- Engagement metrics, seperti Social Shares, Email Opens, dan Email Clicks, yang tinggi, terutama di kampanye 7995 dan 7998.
- Loyalty Points dan Previous Purchases yang lebih tinggi, yang kemungkinan meningkatkan probabilitas konversi.

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
