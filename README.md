

---

```markdown
# 📩 Email / SMS Spam Classifier

A simple Machine Learning project that classifies text messages (emails/SMS) as Spam or Not Spam using Naïve Bayes and CountVectorizer.  
Built with Scikit-learn and deployed using Streamlit.

🔗 Live Demo: [Try it here!](https://emailspamclassifier-roogpzwt4pmtqrylmxbage.streamlit.app/)

---

## 🚀 Features
- ✅ Classifies messages into Spam or Not spam 
- ✅ Shows confidence score of the prediction  
- ✅ Clean and interactive Streamlit UI 
- ✅ Trained on the popular [SMS Spam Collection Dataset (UCI ML Repo)](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)  

---

## 📂 Project Structure
```

EmailSpamClassifier/
│── app.py              # Streamlit app (frontend)
│── spam\_model.pkl      # Saved model + vectorizer (pickle)
│── requirements.txt    # Dependencies for deployment
│── README.md           # Project documentation

````

---

## ⚙️ How It Works
1. Vectorization  
   - The text is converted into numerical features using CountVectorizer.  
2. Classification  
   - A Multinomial Naïve Bayes classifier predicts whether the message is spam or not.  
3. Result Display  
   - Shows prediction result with a confidence percentage.  

---

## 📦 Installation & Usage
Clone the repo:
```bash
git clone https://github.com/hammadshah18/EmailSpamClassifier.git
cd EmailSpamClassifier
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

Then open in your browser: `http://localhost:8501`

---

## 📊 Example Predictions

| Message                                 | Prediction | Confidence |
| --------------------------------------- | ---------- | ---------- |
| "Win cash now! Call this number!"       | Spam       | 97%        |
| "Are we still on for the 3 PM meeting?" | Not Spam   | 94%        |
| "You have been selected for a prize"    | Spam       | 92%        |

---

## 🛠️ Tech Stack

* [Python](https://www.python.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [Streamlit](https://streamlit.io/)
* [Pandas](https://pandas.pydata.org/)

---

## 📌 Future Improvements

* Add **visualizations** (word frequency, confusion matrix, ROC curve)
* Improve preprocessing (stopwords removal, stemming/lemmatization)
* Try advanced models (Logistic Regression, Random Forest, Transformers)
* Support for multiple languages

---

## 👨‍💻 Author

Developed by **[Shazaib Aslam](https://github.com/hammadshah18)**

💡 Contributions, issues, and feature requests are welcome!
