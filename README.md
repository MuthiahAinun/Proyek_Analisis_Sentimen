# Proyek_Analisis_Sentimen
---
# 💡 Sentiment Analysis with Deep Learning

## 📌 Deskripsi
Proyek ini bertujuan untuk melakukan analisis sentimen teks menggunakan berbagai algoritma machine learning. Model yang digunakan mencakup Random Forest dan XGBoost, dengan teknik ekstraksi fitur seperti Word2Vec dan TF-IDF. Selain itu, PCA diterapkan untuk meningkatkan efisiensi model.

Pada tahap pelabelan, digunakan **VADER** Sentiment Analysis untuk teks berbahasa Inggris dan **IndoBERT** (Hugging Face Transformer) untuk teks berbahasa Indonesia. Untuk memastikan pemrosesan yang tepat, diterapkan fungsi deteksi bahasa otomatis yang mengidentifikasi bahasa dalam dataset sebelum melakukan analisis sentimen.

Proyek ini dikembangkan menggunakan Python dan pustaka Scikit-learn, Gensim, serta XGBoost. Model yang dibangun akan mengklasifikasikan sentimen ke dalam tiga kategori: Positif, Netral, dan Negatif.

---

## 🗃️ Dataset
| **Username**       | **Text**                                                                                   | **Likes** | **Published At**        |
|--------------------|--------------------------------------------------------------------------------------------|---------- |-------------------------|
| @MrBeast           | BEAST GAMES FINALE DROPS FEBRUARY 13TH! GO WATCH!                                          | 54600     | 2025-02-08T16:59:31Z    |
| @SultanRayyan-7    | Saya orang Indonesia 🇮🇩🇮🇩                                                                   | 0         | 2025-03-19T21:51:42Z    |
| @ILoveyou-954      | বাংলাদেশ আসবেন কবে পাবনা জেলার কিছু দেখতে চাই	                                            | 0         | 2025-03-19T21:51:42Z    |
| @Moneymakerarab    | This is for girls listen to Dalida - Helwa ya Baladi                                       | 0         | 2025-03-19T21:51:42Z    |


```Dataset ini berisi beberapa kolom:```
- username: Nama pengguna yang memberikan komentar.
- text: Teks opini atau komentar.
- likes: Jumlah suka pada komentar.
- published_at: Waktu publikasi komentar.

## 🏗️ Arsitektur Model
Proyek ini terdiri dari 3 skema pemodelan sebagai berikut:

`🚀 Skema 1: Random Forest + Word2Vec + PCA`
Menggunakan algoritma Random Forest untuk klasifikasi, dengan fitur diekstraksi menggunakan Word2Vec untuk representasi kata. PCA (Principal Component Analysis) diterapkan untuk mengurangi dimensi fitur dan meningkatkan efisiensi model.

`🌊 Skema 2: Random Forest + TF-IDF`
Menggunakan Random Forest sebagai model klasifikasi dengan fitur yang diekstraksi menggunakan TF-IDF (Term Frequency-Inverse Document Frequency). Pendekatan ini menangkap pentingnya kata dalam dokumen untuk meningkatkan performa klasifikasi.

`🌐 Skema 3: XGBoost + TF-IDF`
Menggunakan XGBoost, algoritma berbasis pohon yang dioptimalkan untuk performa tinggi, dengan fitur diekstraksi menggunakan TF-IDF. Kombinasi ini bertujuan untuk meningkatkan akurasi dalam klasifikasi teks.

## ⚙️ Instalasi
Pastikan Anda menggunakan Python 3.x dan instal dependensi dengan perintah berikut:

```sh
pip install -r requirements.txt
```

## 📝 Evaluasi Model
Model menghasilkan metrik evaluasi berupa:

🎯 Akurasi

📝 Precision

🔁 Recall

🌟 F1-Score

## 🗃️ Struktur Folder
```
├── NDsO1LT_0lw_youtube_comments.csv                                      # File dataset
├── Scraping_Proyek_Analisis_Sentimen_Tsamarah_Muthi'ah_A.ipynb           # File Scraping
├── Proyek_Analisis_Sentimen_Tsamarah_Muthi'ah_A.ipynb                    # File Skema 1, Skema 2, Skema 3
├── requirements.txt                                                      # Daftar dependensi
└── README.md                                                             # Dokumentasi proyek
```

## 💡 Kontribusi
Kontribusi sangat diterima! Jika Anda memiliki ide atau saran, silakan buat Pull Request atau ajukan Issue. 😊

📧 Hubungi saya melalui [GitHub](https://github.com/MuthiahAinun) jika ada pertanyaan.
