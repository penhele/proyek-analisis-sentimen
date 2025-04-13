# 🚖 Analisis Sentimen Aplikasi Gojek

Proyek ini bertujuan untuk menganalisis sentimen dari ulasan pengguna terhadap aplikasi **Gojek** menggunakan pendekatan *machine learning* dan *deep learning*. Analisis ini membantu memahami persepsi publik terhadap layanan Gojek, yang berguna untuk pengambilan keputusan berbasis data.

Saya menggunakan tiga pendekatan berbeda untuk membandingkan performa model berdasarkan akurasi dan F1-Score. Dataset terdiri dari lebih dari 22.000 data ulasan pengguna yang telah melalui proses praproses dan pelabelan.

## 📊 Perbandingan Model

| ID | Model          | Accuracy | F1-Score | Split Ratio | Feature Type     |
|----|----------------|----------|----------|--------------|------------------|
| 2  | LSTM           | 94.60%   | 94.17%   | 80/20        | Word Embedding   |
| 1  | SVM            | 92.28%   | 91.80%   | 80/20        | TF-IDF           |
| 0  | Random Forest  | 85.75%   | 84.30%   | 70/30        | TF-IDF           |

Model LSTM memberikan performa terbaik dalam eksperimen ini, diikuti oleh SVM dan Random Forest.