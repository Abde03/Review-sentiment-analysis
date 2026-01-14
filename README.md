# Sentiment Analysis of Amazon Reviews

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-purple)
![TF--IDF](https://img.shields.io/badge/Vectorization-TF--IDF-yellow)
![SVM](https://img.shields.io/badge/Model-Linear%20SVM-lightgrey)
[![Streamlit App](https://img.shields.io/badge/Live%20App-Streamlit-brightgreen)](https://review-sentiment-analyse.streamlit.app/)

This repository contains a complete machine learning project that classifies online product reviews into three sentiment categories: **negative**, **neutral**, and **positive**. The trained model is deployed as a **Streamlit web application** accessible at:

👉 https://review-sentiment-analyse.streamlit.app/

---

## 🧠 Project Overview

Sentiment analysis is the process of automatically identifying the emotional tone behind a piece of text. In e-commerce, this helps understand customer satisfaction at scale.

This project demonstrates:
- Data preprocessing
- Natural Language Processing (NLP)
- Model training and evaluation
- Deployment of an interactive app

---

## 🗂️ Dataset

We use Amazon Product Reviews with the following transformations:

| Score | Sentiment |
|-------|-----------|
| 1–2   | Negative  |
|   3   | Neutral   |
| 4–5   | Positive  |


The dataset was cleaned and transformed to a CSV with the following format:

label,text
positive,"This product was excellent and fast!"
neutral,"It's okay, does what it should."
negative,"Very disappointed, stopped working."

---

## 🧠 Model Training

The machine learning pipeline includes:

1. **Text cleaning**
2. **TF-IDF Vectorization**
3. **Linear SVM classifier**
4. **Class balancing** to improve prediction on the neutral category
5. **Train/test split**
6. **Model evaluation**

The trained model is saved as:

sentiment_model.pkl

---

## 🚀 Deployment

The trained model is deployed as a web app using Streamlit.

Features :
- Real-time sentiment prediction 
- User-friendly interface
- Works with any text input
- Shows how NLP and ML integrate into a simple UI

📍 Live app: https://review-sentiment-analyse.streamlit.app/

---

## 🧠 Future Improvements

Possible enhancements include:

- Experiment with transformer-based models (BERT, RoBERTa)
- Add multilingual support
- Provide more interpretability for predictions
- Export as REST API (FastAPI / Flask)

---

## 📬 Contact

For questions or improvements, feel free to contact me :)
