# 📧 Spam Email Classifier

This project uses machine learning to tell if a message is spam or not.

## 📂 About

It takes a list of text messages. Each message is marked as "spam" or "not spam".  
The messages are cleaned and converted into numbers using TF-IDF.  
A model is then trained to spot patterns and make predictions.

## ⚙️ What It Uses

- Python  
- Pandas  
- scikit-learn  
- NLTK  
- TF-IDF  
- SVM and Naive Bayes

## 🧠 How It Works

1. Loads the data (`spam.csv`)
2. Cleans the message text
3. Splits the data into training and test sets
4. Uses TF-IDF to turn words into numbers
5. Trains a machine learning model
6. Tests how well it works
7. Can predict if a new message is spam

## 🚀 Try It

You can test it with your own message using:

```python
predict_message("Win a free iPhone now!")
```

## ✅ Sample Result

```
SPAM ⚠️
```

## 📁 Files

- `spam.csv` – dataset with labeled messages  
- `Spam_Email_Classifier.ipynb` – the main notebook with code and output  
- `spam_classifier.pkl` – the saved model (optional)

## 🙌 Author

Made as part of an internship project to learn machine learning and text classification.
