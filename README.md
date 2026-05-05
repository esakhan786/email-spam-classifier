#  Email/SMS Spam Classifier

A simple Machine Learning web app that classifies messages as **Spam** or **Not Spam** using Natural Language Processing (NLP).

---

##  Project Overview

This project uses text preprocessing and a trained ML model to detect spam messages.
The app is built using **Streamlit** for a simple and interactive UI.

---

##  Technologies Used

* Python
* Scikit-learn
* NLTK
* Streamlit
* TF-IDF Vectorizer
* Naive Bayes Model

---

##  How It Works

1. User enters a message
2. Text is preprocessed (lowercase, tokenization, stopword removal, stemming)
3. TF-IDF converts text into numerical form
4. Model predicts whether message is spam or not

---

##  Project Structure

```
email-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---

##  Run the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run app.py
```

---

##  Example

Input:

```
Congratulations! You won a free ticket. Click now!
```

Output:

```
Spam
```

---

##  Future Improvements

* Improve model accuracy
* Add deep learning models (LSTM/RNN)
* Deploy online (Heroku / Streamlit Cloud)

---

##  Author

Esa Khan

---
