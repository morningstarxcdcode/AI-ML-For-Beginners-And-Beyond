# 🤖 Project 1: ML Spam Classifier

## ⏱️ Duration: ~1 Hour  

Build a simple spam classifier using Machine Learning that can predict whether a given message is spam or not.

---

## 📌 Goals

- Clean & preprocess text data
- Use TF-IDF Vectorizer for feature extraction
- Train a classifier (e.g., Naive Bayes)
- Evaluate using accuracy, precision, recall
- Predict on new messages

---

## 🧰 Tools & Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🗂️ Dataset

Use [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 🔧 Steps

1. **Import dependencies**  
2. **Load dataset (CSV)**  
3. **Clean and preprocess text**  
   - Lowercase, remove punctuation, stopwords
4. **Convert text to numbers** using `TfidfVectorizer`  
5. **Train classifier** using `MultinomialNB`  
6. **Test accuracy and visualize confusion matrix**
7. **Try custom predictions on your text!**

---

## 📊 Output Sample

---

Accuracy: 98.1% Confusion Matrix: [[...]]

---

## 💡 Ideas to Extend

- Use Logistic Regression / SVM
- Make a web interface using Streamlit
- Add spam keywords heatmap

---

## 🔗 Resources

- [Text Classification with Scikit-learn](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)
