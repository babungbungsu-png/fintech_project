# 💳 Fintech Project

Portfolio ini berisi simulasi **analisa data di sektor fintech** menggunakan dataset dummy (1 juta+ baris, 23 tabel).  
Tujuannya adalah untuk menunjukkan kemampuan **data engineering, exploratory data analysis (EDA), data visualization, hingga menghasilkan business insights** yang relevan untuk industri finansial.

---

## 📂 Struktur Project
- `data/raw/` → dataset mentah (CSV, tidak di-commit, hanya link di Google Drive)
- `data/processed/` → dataset hasil pembersihan (Parquet/CSV)
- `notebooks/` → Jupyter Notebook step-by-step analisa
- `scripts/` → Python scripts (generate data, preprocessing, utilitas)
- `reports/` → PDF report (penjelasan tabel + hasil analisa)
- `results/` → Visualisasi grafik & model output
- `requirements.txt` → daftar library Python yang digunakan

---

## 📊 Dataset
Dataset dummy yang digunakan terdiri dari **23 tabel** yang menggambarkan ekosistem fintech, di antaranya:
- `transactions` (transaksi pembayaran & pinjaman)
- `users` (profil nasabah)
- `loans` (data pinjaman, tenor, bunga)
- `investors` (profil investor & alokasi dana)
- `fraud_logs` (indikasi fraud / anomali)
- `payments` (catatan pembayaran)
- `crm` (interaksi customer service)
- `sla_log` (service level agreement)
- dll.

Dataset **tidak di-commit ke repo (karena >100MB)**.  
👉 [Download Dataset di Google Drive](https://drive.google.com/your-dataset-link)

---

## 🔍 Analisa yang Dilakukan
Beberapa analisa utama yang dilakukan:
- **Revenue Trend** → Analisa pendapatan bulanan & growth
- **Conversion Rate** → Funnel pengguna dari registrasi → transaksi
- **Loan Performance** → Non-Performing Loan (NPL), Repayment Rate
- **Customer Lifetime Value (CLV)** → Segmentasi & prediksi CLV
- **Churn Analysis** → Identifikasi customer yang berhenti bertransaksi
- **Fraud Detection Rate** → Deteksi potensi fraud
- **OPEX Ratio** → Analisa biaya operasional vs revenue
- **Investor Returns** → Tingkat pengembalian dana investor

---

## 📈 Hasil & Insight
- Pendapatan bulanan meningkat 15% QoQ, dengan puncak di Q4.
- CLV lebih tinggi pada customer dengan >3 transaksi per bulan.
- NPL tertinggi ada pada pinjaman dengan tenor >12 bulan.
- Fraud rate cenderung meningkat pada metode pembayaran tertentu.
- Churn dapat diprediksi dengan akurasi 82% menggunakan Random Forest.

*(Detail visualisasi & model tersedia di folder `notebooks/` dan `results/`.)*

---

## 🛠️ Tools
- **Python** → Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Data Viz** → Plotly, Seaborn
- **Reporting** → ReportLab (PDF), Jupyter Notebook
- **Data Generation** → Faker (untuk membuat dataset dummy)
- **Environment** → Jupyter Notebook / Google Colab

---

## 🚀 Cara Menjalankan
1. Clone repository:
   ```bash
   git clone https://github.com/username/fintech_project.git
   cd fintech_project
