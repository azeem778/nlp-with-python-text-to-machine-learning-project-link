# 📧 Spam vs Ham Message Classifier

A machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Logistic Regression and a Bag-of-Words text representation.

## 🔧 Tech Stack

- Python
- Pandas
- Matplotlib
- Scikit-learn (CountVectorizer, Logistic Regression)

## 📊 Workflow

1. Load and explore the SMS dataset (`spam.csv`)
2. Visualize class distribution (Spam vs Ham)
3. Encode labels (`ham` → 0, `spam` → 1)
4. Split data into training and test sets
5. Convert text messages into numerical vectors using `CountVectorizer`
6. Train a `LogisticRegression` model
7. Evaluate accuracy and confusion matrix
8. Test the model with a custom user-input message

## ▶️ How to Run

```bash
pip install pandas matplotlib scikit-learn
jupyter notebook Spam_vs_Ham_Classifier.ipynb
```

Make sure `spam.csv` is in the same directory as the notebook.

## 📁 Dataset

The dataset should contain two columns:

- `Category` — label (`ham` or `spam`)
- `Message` — the SMS text content

## 📈 Output

- Bar chart of spam vs ham message counts
- Model accuracy score
- Confusion matrix visualization
- Live prediction for a custom message
