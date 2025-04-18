# 🛡️ Phishing Detection Using Machine Learning

This project uses machine learning to detect **phishing (scam) emails**, helping to prevent email-based frauds.

It demonstrates how machine learning can be trained on email text data to classify whether an email is **legitimate** or **phishing**.

---

## 📊 Dataset

This project uses a CSV dataset named `phishing_dataset.csv`.

**Columns:**
- `email_text`: The body of the email
- `label`: `1` for phishing, `0` for legitimate

> Note: Ensure your dataset is placed inside the `/data` folder.

---

## 🧠 Model Details

- **Text vectorization:** TF-IDF
- **Classifier:** Logistic Regression
- **Evaluation Metrics:** Accuracy, confusion matrix, precision, recall

You can easily extend this by trying different ML models like:
- Naive Bayes
- Random Forest
- SVM

---

## 🚧 Future Improvements

- Experiment with deep learning models (LSTM, BERT)
- Real-time email scanning via API or web app (Flask/Streamlit)
- Integration with Gmail API for real-time inbox monitoring
- Deployment with Docker or as a web service


