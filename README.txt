# 🧠 Sentiment Analysis using RNN (85% Accuracy)

## 📌 Overview
This project is a Sentiment Analysis model built using Recurrent Neural Network (RNN) to classify text into positive or negative sentiments.  
It processes raw text data and predicts sentiment with high accuracy.

---

## 🚀 Features
- Text Preprocessing using Regex
- Stopwords Removal using NLTK
- Stemming for text normalization
- TF-IDF Vectorization
- RNN Model for sequence learning
- Model Training & Evaluation

---

## 🛠️ Tech Stack
- Python
- PyTorch
- :contentReference[oaicite:0]{index=0}
- Scikit-learn

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing
- Removed special characters using Regex  
- Converted text to lowercase  
- Removed stopwords using NLTK  
- Applied stemming  

### 2️⃣ Feature Extraction
- Used TF-IDF Vectorization to convert text into numerical form  

### 3️⃣ Model Building
- Implemented RNN using PyTorch  
- Used DataLoader for batching  

### 4️⃣ Training & Evaluation
- Trained model on dataset  
- Evaluated using accuracy metric  

---

## 📊 Results
✅ Achieved **85% accuracy** on test dataset  

---

## ▶️ How to Run

```bash
git clone https://github.com/surajyadav98-ai/sentiment-analysis-rnn.git
cd repo-name
pip install -r requirements.txt
python main.py
