Nama: Reyvaldi Febryan Widya Utomo
NIM: 202310370311409

# Case-Based Reasoning (CBR) for Fraud Court Decision Analysis

## Deskripsi
Proyek ini merupakan implementasi metode Case-Based Reasoning (CBR) untuk menganalisis putusan tindak pidana penipuan berdasarkan dokumen putusan pengadilan.

Tahapan yang diimplementasikan meliputi:

- Case Base
- Case Representation
- Case Retrieval
- Case Solution Reuse
- Model Evaluation

## Dataset

Dataset terdiri dari 35 putusan tindak pidana penipuan yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia.

## Tools

- Python
- Google Colab
- pandas
- scikit-learn
- matplotlib
- numpy
- pdfplumber

## Struktur Repository

```
data/
├── raw/
├── processed/

notebooks/
└── Sub_CPMK_3.ipynb
```

## Instalasi

Install dependency:

```bash
pip install -r requirements.txt
```

## Menjalankan Project

1. Buka notebook `Sub_CPMK_3.ipynb`
2. Jalankan seluruh cell dari atas ke bawah.
3. Hasil akan tersimpan pada folder `processed`.

## Output

- cases.csv
- predictions.csv
- evaluation_metrics.csv
