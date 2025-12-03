# capstone-project

# Customer Segmentation Using RFM & K-Means Clustering

Proyek ini bertujuan melakukan segmentasi pelanggan menggunakan metode **RFM (Recency, Frequency, Monetary)** dan algoritma **K-Means Clustering**.  
Hasil segmentasi ini dapat digunakan perusahaan untuk meningkatkan strategi personalisasi, retensi pelanggan, dan efektivitas marketing.

---

## 1. Project Overview
Segmentasi pelanggan dilakukan menggunakan pendekatan berikut:

### **RFM Analysis**
- **Recency**: Seberapa baru pelanggan melakukan transaksi  
- **Frequency**: Seberapa sering pelanggan bertransaksi  
- **Monetary**: Total uang yang dibelanjakan pelanggan  

### **Clustering**
Setelah RFM dihitung, nilai diolah menggunakan **StandardScaler** dan kemudian di-cluster dengan **K-Means** untuk menghasilkan beberapa segmen pelanggan, seperti:
- Pelanggan terbaik  
- Pelanggan loyal  
- Pelanggan potensial  
- Pelanggan berisiko  
- Pelanggan membutuhkan perhatian  

---

## 2. Project Structure
capstone-project/
│
├── capstone_fixed.py # Script preprocessing, RFM, clustering
├── notebook/ # Notebook analisis lengkap
├── data/ # Dataset transaksi pelanggan
├── visualizations/ # Grafik segment summary, boxplot, elbow, pairplot
├── model/ # (Opsional) Model clustering tersimpan
├── README.md # Dokumentasi proyek

## 3. Methods Used

### ✔ Data Preprocessing
- Cleaning data (missing values, duplikasi)
- Filtering transaksi valid
- Feature engineering untuk menghitung nilai RFM

### ✔ Modeling
- Scaling fitur menggunakan StandardScaler
- Clustering menggunakan **K-Means**
- Evaluasi dengan:
  - **Elbow Method**  
  - **Silhouette Score**

### ✔ Visualization
- Boxplot untuk distribusi RFM per cluster
- Pairplot untuk persebaran cluster
- Segment Summary Table
- Elbow Chart untuk menentukan cluster optimal

---

## 4. Key Visualizations

- **Segment Summary Table** → Ringkasan karakteristik setiap cluster  
- **RFM Boxplots** → Distribusi Recency, Frequency, Monetary  
- **Pairplot Cluster** → Visualisasi persebaran cluster berdasarkan fitur  
- **Elbow Method** → Menentukan jumlah cluster optimal  

Semua visualisasi tersedia di folder `visualizations/`.

---

##  5. How to Run the Project

### **1. Clone repository**
```bash
git clone https://github.com/monicavdy03/capstone-project.git

### **2. Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

### **3. Jalankan notebook atau script**
```bash
python capstone_fixed.py

## 6. Team Members
| Nama                    | Role             |
| ----------------------- | ---------------- |
| Putri Ayuningsih        | Machine Learning |
| Azizah Nur Apriliani    | Machine Learning |
| Monika Dian Vidya Putri | Machine Learning |

## 7. Dataset
Dataset yang digunakan:
Customer Segmentation for Personalized Retail Marketing
Berisi data transaksi pelanggan untuk analisis RFM.

