# Proyek Analisis Data: E-Commerce Public Dataset 🛍️

Proyek ini adalah tugas akhir dari kelas "Belajar Analisis Data dengan Python" di Dicoding. Proyek ini bertujuan untuk menganalisis data E-Commerce, mengidentifikasi pola pembelian pelanggan, performa produk, serta membuat dashboard interaktif menggunakan Streamlit.

## 📂 Struktur Proyek
submission 
├── dashboard 
│ ├── dashboard.py 
│ └── all_data.csv 
├── notebook.ipynb 
├── README.md 
├── requirements.txt 
└── url.txt

## 🚀 Cara Menjalankan Dashboard (Lokal)

Jika Anda ingin menjalankan dashboard ini di komputer lokal Anda, silakan ikuti langkah-langkah di bawah ini:

### 1. Setup Environment - Anaconda
bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

### 2. Setup Environment - Shell/Terminal
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

### 3. Menjalankan Streamlit
streamlit run dashboard/dashboard.py

📊 Gambaran Analisis
Proyek ini mencakup beberapa tahapan analisis data:

Data Wrangling: Mengumpulkan data dari berbagai tabel CSV, membersihkan data (missing values, tipe data), dan menggabungkannya menjadi satu dataset utama.
Exploratory Data Analysis (EDA): Mengeksplorasi data untuk menjawab pertanyaan bisnis seperti:
Produk apa yang paling laris dan paling sedikit terjual?
Bagaimana demografi pelanggan berdasarkan lokasi (State)?
Advanced Analysis (RFM Analysis): Mengelompokkan pelanggan terbaik berdasarkan teknik Recency, Frequency, dan Monetary.
Visualization & Dashboard: Menyajikan hasil analisis dalam bentuk grafik interaktif yang mudah dipahami.

🔗 Tautan Dashboard
Dashboard yang telah dideploy dapat diakses melalui tautan berikut: Klik di sini untuk melihat Dashboard
