# Stuntfree - Backend & Web System

Sistem Prediksi Stunting dan Intervensi Gizi Adaptif Berbasis Machine Learning.

## Tech Stack
- **Framework:** Flask (Python)
- **Backend-as-a-Service (BaaS):** Appwrite Cloud
- **ML Integration:** Scikit-Learn

## Cara Menjalankan Lokal
1. Clone repositori ini.
2. Buat virtual environment: `python -m venv venv && source venv/bin/activate`
3. Install dependensi: `pip install -r requirements.txt`
4. Buat berkas `.env` dan isi kredensial Appwrite.
5. Jalankan setup database: `python setup_db.py`
6. Jalankan server Flask: `python run.py`
EOF

git add README.md
git commit -m "docs: tambahkan dokumentasi dasar README"
git push
