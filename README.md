📧 Spam Email Detection with TF-IDF and Naive Bayes

This project demonstrates a Spam Email Detection System built using TF-IDF Vectorization and a Naive Bayes Classifier.
The model is able to classify emails as Spam or Ham (Not Spam) with high accuracy.

🚀 Project Overview

Goal: Detect whether an email is spam or not based on its content.

Dataset: https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset

Model: Multinomial Naive Bayes trained on TF-IDF features.

Accuracy: 97.57% on the test set.

⚙️ Workflow

Data Preprocessing

Lowercasing text

Removing stopwords, punctuation, and non-alphabetic characters

Lemmatization and stemming

Feature Extraction

Convert text into numerical features using TF-IDF Vectorizer

Model Training

Train a Multinomial Naive Bayes classifier on TF-IDF features

Evaluation

Accuracy: 97.57%

Confusion matrix to analyze predictions

📊 Results

Accuracy: 97.57%

Confusion Matrix

	Predicted Ham	Predicted Spam
Actual Ham	11641	177
Actual Spam	430	  12787

Example Prediction:

Input: "Congratulations! You won a free lottery ticket. Claim now."
Output: Spam (95.6%)

🛠️ Tech Stack

Python

scikit-learn

NLTK

NumPy & Pandas

Matplotlib & Seaborn

📂 Project Structure
spam-detection/
│── data/               # Dataset
│── notebook.ipynb      # Jupyter notebook with training & evaluation
│── README.md           # Documentation

🔮 Future Improvements

Deploy as a web app using Streamlit or Gradio

Experiment with advanced models (Logistic Regression, SVM, Deep Learning)

Handle multilingual spam detection

✨ Conclusion

This project shows that TF-IDF + Naive Bayes is a simple yet powerful approach for spam detection, achieving 97.57% accuracy with lightweight computation.
