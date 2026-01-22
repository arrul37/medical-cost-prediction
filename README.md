# Analisis Prediksi Biaya Medis Personal (Medical Cost Prediction)

Proyek ini bertujuan untuk memprediksi estimasi biaya tagihan medis (*medical charges*) menggunakan algoritma Machine Learning **Random Forest Regression**. Proyek ini disusun sebagai pemenuhan Tugas Akhir mata kuliah Big Data dan Data Mining.

## 📌 Gambaran Umum
Biaya asuransi kesehatan dipengaruhi oleh banyak faktor seperti usia, BMI, dan status merokok. Model ini dilatih untuk mempelajari pola tersebut dan memberikan estimasi biaya yang akurat.

* **Algoritma:** Random Forest Regressor
* **Akurasi Model:** R2 Score 0.86 (86%)
* **Fitur Utama:** Usia, BMI, Status Perokok, Jumlah Anak, Wilayah

## 📂 Struktur File
* `medical_cost_prediction.ipynb`: Source code lengkap (Jupyter Notebook)
* `insurance.csv`: Dataset yang digunakan
* `model_random_forest.pkl`: Model Random Forest yang sudah dilatih
* `UAS_ULUM_23.11.5524.pdf`: Laporan analisis lengkap
* `requirements.txt`: Dependency Python yang diperlukan

## 🚀 Cara Menjalankan

### Dengan Virtual Environment (Recommended)
1. **Clone repository ini:**
   ```bash
   git clone <repository-url>
   cd medical-cost-prediction
   ```

2. **Buat virtual environment:**
   - **Linux/macOS:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install library yang dibutuhkan:**
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. **Jalankan Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Kemudian buka file `medical_cost_prediction.ipynb` di browser.

5. **Deaktivasi virtual environment (setelah selesai):**
   ```bash
   deactivate
   ```

### Tanpa Virtual Environment
1. Clone repository ini.
2. Install library yang dibutuhkan: `pip install -r requirements.txt`
3. Jalankan file notebook `.ipynb` menggunakan Jupyter Notebook atau Google Colab.

## 👨‍💻 Pembuat
* **Nama:** Ahmad Natsrul Ulum
* **NIM:** 23.11.5524
* **Universitas Amikom Yogyakarta**