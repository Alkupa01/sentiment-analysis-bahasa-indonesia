# Sentiment Analysis Bahasa Indonesia 🇮🇩  
Project portofolio AI sederhana yang melakukan klasifikasi sentimen (positif, negatif, netral) pada teks Bahasa Indonesia menggunakan model IndoBERT.

## 📌 Tujuan Project
- Belajar dasar NLP dengan Bahasa Indonesia  
- Melatih model klasifikasi sentimen menggunakan pretrained model  
- Menunjukkan kemampuan menggunakan HuggingFace, Transformers, dan Python  
- Menjadi portofolio AI/ML engineer pemula

---

## 📂 Struktur Project
sentiment-analysis-bahasa-indonesia/
│── README.md
│── notebook.ipynb
│── requirements.txt
└── data/
└── (dataset otomatis dari HuggingFace)


---

## 📦 Requirements
Semua library ada di `requirements.txt`, namun yang utama adalah:

- Python 3.9+
- transformers
- datasets
- torch
- scikit-learn
- jupyter notebook

Install dengan:
pip install -r requirements.txt


---

## 🧠 Model yang Digunakan
Model: **indobenchmark/indobert-base-p1**  
Sumber: HuggingFace IndoNLU

Model ini di-fine-tune untuk klasifikasi sentimen:
- 0 → Negative  
- 1 → Neutral  
- 2 → Positive  

---

## 🧪 Cara Menjalankan Notebook
1. Buka Jupyter Notebook  
2. Jalankan `notebook.ipynb`  
3. Notebook berisi:
   - Load dataset  
   - Tokenisasi  
   - Training  
   - Evaluation  
   - Testing manual input

---

## 📝 Contoh Penggunaan
Input:  
“Aku suka banget aplikasi ini!”

Output:  
**Positive**

---

## 🏁 Status Project
Masih tahap awal. Rencana peningkatan:
- Tambah visualisasi (confusion matrix & data distribution)
- Deploy ke HuggingFace Spaces (Gradio UI)
- Menambah dataset custom

---

## 👤 Author
Albert Kurniawan  
Mahasiswa AI • Universitas Ciputra Surabaya

