# Case-Based Reasoning (CBR) for Fraud Court Decision Analysis

- **Nama** : Reyvaldi Febryan Widya Utomo
- **NIM** : 202310370311409
- **Mata Kuliah** : Penalaran Komputer D

---

# Deskripsi

Project ini mengimplementasikan metode **Case-Based Reasoning (CBR)** untuk menganalisis putusan tindak pidana penipuan menggunakan dokumen putusan pengadilan.

Pipeline yang diimplementasikan terdiri dari:

1. Case Base
2. Case Representation
3. Retrieve
4. Reuse
5. Evaluation

---

# Struktur Repository

```
.
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   └── Sub_CPMK_3.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Instalasi

Clone repository

```bash
git clone https://github.com/USERNAME/NAMA_REPOSITORY.git
```

Masuk ke folder project

```bash
cd NAMA_REPOSITORY
```

Install seluruh library

```bash
pip install -r requirements.txt
```

---

# Cara Menjalankan Pipeline

Jalankan notebook menggunakan Google Colab atau Jupyter Notebook.

Urutan eksekusi:

1. Buka file `notebooks/Sub_CPMK_3.ipynb`
2. Jalankan seluruh cell dari atas ke bawah (Run All)
3. Sistem akan:
   - Membaca dokumen putusan
   - Melakukan preprocessing
   - Mengekstraksi metadata
   - Membentuk Case Base
   - Melakukan Retrieval menggunakan TF-IDF dan Cosine Similarity
   - Melakukan klasifikasi menggunakan Support Vector Classifier (SVC)
   - Menghasilkan evaluasi model

---

# Output

Program menghasilkan beberapa file pada folder `data/processed`.

- `cases.csv`
- `predictions.csv`
- `evaluation_metrics.csv`

---

# Library yang Digunakan

- pandas
- numpy
- matplotlib
- scikit-learn
- pdfplumber

---

# Dataset

Dataset terdiri dari 35 dokumen putusan tindak pidana penipuan yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia.
