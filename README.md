# 📰 Fake News Prediction  

This project is an attempt to build a Fake News prediction using machine learning techniques.  

## 📌 Overview  
The model is trained on a labeled dataset of news articles (fake/real).  
I applied text preprocessing (tokenization, stopword removal, TF-IDF vectorization)  
and trained a classification model.  

- **Training Accuracy:** ~78%  
- **Testing Accuracy:** ~49%  

## ❓ Problem  
While the model performs decently on training data, it fails to generalize well on unseen test data.  
This looks like **overfitting**, and I’m still exploring ways to fix it.  

## ⚡ Next Steps  
I would love feedback on:  
- Why the model struggles to generalize.  
- How to improve accuracy on unseen data.  
- Possible enhancements in preprocessing, feature engineering, or hyperparameter tuning.  

## 🚀 How to Run  
```bash
pip install -r requirements.txt
python fake_news.py
