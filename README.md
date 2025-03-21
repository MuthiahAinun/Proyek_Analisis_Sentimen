# Proyek_Analisis_Sentimen

# 💡 Sentiment Analysis with Deep Learning

Proyek ini bertujuan untuk melakukan analisis sentimen pada teks menggunakan berbagai algoritma deep learning. Model yang digunakan antara lain LSTM, CNN, dan GRU dengan berbagai teknik ekstraksi fitur seperti Tokenizer, Word2Vec, dan TF-IDF. Proyek ini dikembangkan menggunakan Python dan TensorFlow.

## 📌 Deskripsi
Proyek ini bertujuan untuk melakukan analisis sentimen pada teks menggunakan berbagai algoritma deep learning. Model yang digunakan antara lain LSTM, CNN, dan GRU dengan berbagai teknik ekstraksi fitur seperti Tokenizer dan Word2Vec. Proyek ini dikembangkan menggunakan Python dan TensorFlow. 
Model deep learning digunakan untuk mengklasifikasikan sentimen menjadi **Positif**, **Netral**, dan **Negatif**.

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

`🚀 Skema 1: LSTM + Tokenizer`
Menggunakan LSTM (Long Short-Term Memory) untuk memproses urutan teks.
Fitur diekstraksi menggunakan Tokenizer.

`🌊 Skema 2: CNN + Word2Vec`
Menggunakan CNN (Convolutional Neural Network) untuk ekstraksi fitur spasial.
Memanfaatkan Word2Vec untuk representasi kata.

`🌐 Skema 3: GRU + Word2Vec`
Menggunakan GRU (Gated Recurrent Unit) untuk pemrosesan teks berurutan.
Menggunakan Word2Vec sebagai teknik embedding.

## ⚙️ Instalasi
Pastikan Anda menggunakan Python 3.x dan instal dependensi dengan perintah berikut:

```pip install -r requirements.txt```

## 📝 Evaluasi Model
Model menghasilkan metrik evaluasi berupa:

🎯 Akurasi
📝 Precision
🔁 Recall
🌟 F1-Score

## 🗃️ Struktur Folder
├── data/                   # Folder dataset
├── models/                 # Folder model terlatih
├── scripts/                # Folder skrip Python
├── requirements.txt        # Daftar dependensi
├── sentiment_analysis.py   # Skrip utama
└── README.md               # Dokumentasi proyek

## 💡 Kontribusi
Kontribusi sangat diterima! Jika Anda memiliki ide atau saran, silakan buat Pull Request atau ajukan Issue. 😊
