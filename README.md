# 📊 Customer Segmentation Using RFM & K-Means Clustering

Proyek ini bertujuan melakukan **segmentasi pelanggan** menggunakan
metode **RFM (Recency, Frequency, Monetary)** dan algoritma **K-Means
Clustering**.\
Hasil segmentasi digunakan untuk meningkatkan strategi personalisasi,
retensi pelanggan, dan efektivitas kampanye marketing.

------------------------------------------------------------------------

## 🚀 1. Project Overview

Segmentasi dilakukan menggunakan dua pendekatan utama:

### **🔹 RFM Analysis**

-   **Recency** --- Seberapa baru pelanggan terakhir bertransaksi\
-   **Frequency** --- Seberapa sering pelanggan bertransaksi\
-   **Monetary** --- Total jumlah uang yang dibelanjakan pelanggan

### **🔹 K-Means Clustering**

Setelah nilai RFM dihitung dan distandardisasi, pelanggan dikelompokkan
menjadi beberapa segmen, seperti:

-   Best Customers\
-   Loyal Customers\
-   Potential Customers\
-   At-Risk Customers\
-   Customers Needing Attention

------------------------------------------------------------------------

## 📁 2. Project Structure

    capstone-project/
    │
    ├── capstone_fixed.py       # Script preprocessing, RFM computation, clustering
    ├── notebook/               # Notebook analisis lengkap
    ├── data/                   # Dataset transaksi pelanggan
    ├── visualizations/         # Grafik: segment summary, boxplot, elbow, pairplot
    ├── model/                  # (Opsional) Trained clustering model
    ├── README.md               # Dokumentasi proyek

------------------------------------------------------------------------

## 🛠 3. Methods Used

### ✔ **Data Preprocessing**

-   Cleaning data (missing values, duplikasi)
-   Filtering transaksi valid
-   Feature engineering untuk menghitung nilai RFM

### ✔ **Modeling**

-   Standarisasi fitur menggunakan **StandardScaler**
-   Clustering menggunakan **K-Means**
-   Evaluasi menggunakan:
    -   **Elbow Method**
    -   **Silhouette Score**

### ✔ **Visualization**

-   Boxplot distribusi RFM berdasarkan cluster\
-   Pairplot persebaran cluster\
-   Segment Summary Table\
-   Elbow Chart penentuan jumlah cluster optimal

Semua grafik disimpan di folder **visualizations/**.

------------------------------------------------------------------------

## 📊 4. Key Visualizations

-   Segment Summary Table\
-   RFM Boxplots\
-   Cluster Pairplot\
-   Elbow Method Chart

------------------------------------------------------------------------

## ▶ 5. How to Run the Project

### 1. Clone repository

``` bash
git clone https://github.com/monicavdy03/capstone-project.git
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Jalankan script atau notebook

``` bash
python capstone_fixed.py
```

------------------------------------------------------------------------

## 👥 6. Team Members

  Nama                      Role
  ------------------------- ------------------
  Putri Ayuningsih          Machine Learning
  Azizah Nur Apriliani      Machine Learning
  Monika Dian Vidya Putri   Machine Learning

------------------------------------------------------------------------

## 📚 7. Dataset

Dataset yang digunakan:

**Customer Segmentation for Personalized Retail Marketing**\
Berisi data transaksi pelanggan yang digunakan untuk perhitungan RFM dan
clustering.
