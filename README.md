# Proyek_Analisis_Sentimen
---
# 💡 Sentiment Analysis with Deep Learning

## 📌 Description
This project aims to perform sentiment analysis on text data using various machine learning algorithms. The models used include Random Forest and XGBoost, with feature extraction techniques such as Word2Vec and TF-IDF. Additionally, PCA is applied to enhance model efficiency.

For the labeling stage, **VADER** Sentiment Analysis is used for English texts, while **IndoBERT** (Hugging Face Transformer) is applied for Indonesian texts. To ensure proper processing, an automatic language detection function is implemented to identify the language in the dataset before performing sentiment analysis.

The project is developed using Python and leverages libraries such as Scikit-learn, Gensim, and XGBoost. The resulting model classifies sentiment into three categories: Positive, Neutral, and Negative.

---

## 🗃️ Dataset
| **Username**       | **Text**                                                                                   | **Likes** | **Published At**        |
|--------------------|--------------------------------------------------------------------------------------------|---------- |-------------------------|
| @MrBeast           | BEAST GAMES FINALE DROPS FEBRUARY 13TH! GO WATCH!                                          | 54600     | 2025-02-08T16:59:31Z    |
| @SultanRayyan-7    | Saya orang Indonesia 🇮🇩🇮🇩                                                                   | 0         | 2025-03-19T21:51:42Z    |
| @ILoveyou-954      | বাংলাদেশ আসবেন কবে পাবনা জেলার কিছু দেখতে চাই	                                            | 0         | 2025-03-19T21:51:42Z    |
| @Moneymakerarab    | This is for girls listen to Dalida - Helwa ya Baladi                                       | 0         | 2025-03-19T21:51:42Z    |


This dataset contains the following columns:
- **username**: The name of the user who posted the comment.
- **text**: The opinion or comment text.
- **likes**: The number of likes received by the comment.
- **published_at**: The timestamp of when the comment was published.

## 🏗️ Model Architecture
This project consists of three modeling schemes as follows:

`🚀 Scheme 1: Random Forest + Word2Vec + PCA`  
Uses the Random Forest algorithm for classification, with features extracted using Word2Vec for word representation. PCA (Principal Component Analysis) is applied to reduce feature dimensionality and improve model efficiency.

`🌊 Scheme 2: Random Forest + TF-IDF`  
Utilizes Random Forest as the classification model with features extracted using TF-IDF (Term Frequency-Inverse Document Frequency). This approach captures the importance of words within documents to enhance classification performance.

`🌐 Scheme 3: XGBoost + TF-IDF`  
Employs XGBoost, a high-performance tree-based algorithm, with features extracted using TF-IDF. This combination aims to improve accuracy in text classification.

## ⚙️ Installation
Make sure you are using Python 3.x and install the required dependencies by running the following command:

```sh
pip install -r requirements.txt
```

## 📝 Model Evaluation
The model produces the following evaluation metrics:

🎯 Akurasi

📝 Precision

🔁 Recall

🌟 F1-Score

## 🗃️ Folder Structure
```
├── NDsO1LT_0lw_youtube_comments.csv                                           # Dataset file
├── Scraping_Proyek_Analisis_Sentimen_Tsamarah_Muthi'ah_A.ipynb                # Scraping script
├── Proyek_Analisis_Sentimen_Tsamarah_Muthi'ah_A.ipynb                         # Main notebook for Scheme 1, 2, and 3
├── dataset_labeled.pkl                                                        # Labeled sentiment dataset
├── requirements.txt                                                           # List of dependencies
└── README.md                                                                  # Project documentation
```

## 💡 Contributions
Contributions are very welcome! If you have any ideas or suggestions, feel free to create a Pull Request or open an Issue. 😊

📧 Contact me via [GitHub](https://github.com/MuthiahAinun) if you have any questions.
