# 🧑🏻‍💻 NPL Project 🧑🏻‍💻
This repository contains a project for a basic NPL model.

---

## 📌 Project Overview
This project follows the guidelines to build a text-classification model to distinguish **real news** from **fake news**.

## 📁 Project Structure
- `npl_Project_vf.ipynb`: Jupyter Notebook with the full analysis.
- `Fake_news_detection.pdf`: PDF presentation summarizing the process.
- `testing_data.csv`, `training_data.csv` and `new_testing_data.csv` : CSV files containing the datasets used.

## 🗂 Dataset
- The main dataset was given by Ironhack.
- It contains 34152 rows with uncleaned text divided in fake news and real news.
- There were no missing values in the dataset.


## 🛠️ Tech Stack
All the data analysis and model construction was done using:
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- sklearn
- NLTK
- Also, as a bonus development, a model was created with a transformer: **distilBERT**

## 🧩 Data Modeling
- The original dataset stored the news in a single column with different structures.
- The text data was treated with: tokenization, lowercasing, remove punctuation, remove stopwords and finally lemmatized.


## 📈 Key Insights
- **Cleaned vs uncleaned data**:
  - The results show a better accuracy in all models tested with uncleaned data.
  - There's important information for the model that can be lost if the data is too much cleaned.
- **CountVectorizer vs TF-IDF**:
  - There were minimal differences between the two vectorizers.
  - However, the confusion matrix shows more balance in TF-IDF
- **distilBERT**:
  - Most of the previous work can be done by a transformer, and with better result.


## 🥷 Teamwork

Built together with @[Marius Gören](https://github.com/MariusGoeren)
