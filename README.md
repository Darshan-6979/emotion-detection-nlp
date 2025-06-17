# emotion-detection-nlp
🔍 Detect emotions like joy, sadness, anger, fear, love, and surprise from English text using NLP and machine learning. Final project of internship ML series.
# 💬 Emotion Detection from Text using ML

This project builds a machine learning model to detect the emotional tone in English sentences. It classifies text into emotions like joy, sadness, anger, fear, love, and surprise.

---

## 📊 Dataset

- Source: [Emotions Dataset on Kaggle](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- Files used:
  - `train.txt`
  - `test.txt`
  - `val.txt`
- Each file contains `text;emotion` format

---

## 🧠 Model Details

| Step        | Method                    |
|-------------|---------------------------|
| Preprocessing | Lowercasing, stopword removal (via TF-IDF)  
| Vectorization | `TfidfVectorizer`  
| Model        | `LogisticRegression` (scikit-learn)  
| Accuracy     | ✅ 87.7% on test set

---

## 🔮 Sample Prediction

```python
predict_emotion("I feel like screaming") → anger  
predict_emotion("This made me smile all day") → joy  
