# Resume Classifier using NLP & Machine Learning

An end-to-end machine learning pipeline that automatically classifies resumes into predefined job categories using **Natural Language Processing (NLP)**.

This project demonstrates:
- Cleaning and processing text using **spaCy**
- Extracting meaningful features using **TF-IDF**
- Training a **Logistic Regression** model for multi-class classification

It’s an excellent starting point for applied NLP projects.

---

## 🚀 Key Steps

### 1. Text Preprocessing (spaCy)
- Tokenization
- Lowercasing
- Stopword Removal
- Lemmatization

### 2. Feature Extraction
- **TF-IDF Vectorization** to convert cleaned text into numerical feature vectors.

### 3. Model Training
- **Logistic Regression** for multi-class classification of resumes.

### 4. Model Evaluation
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)
- Predicts job categories from raw resume text

---

## 🛠 Tech Stack

- **Python 3.x** – Programming language
- **spaCy** – Text preprocessing (`en_core_web_sm`)
- **Scikit-learn** – Model building, training & evaluation
- **Pandas** – Data handling & manipulation
- **NumPy** – Numerical computations

---

## 📂 Project Workflow

1. **Preprocessing**  
   Clean and lemmatize raw resume text using spaCy.

2. **Feature Engineering**  
   Convert processed text into feature vectors using TF-IDF.

3. **Classification**  
   Train a Logistic Regression model to classify resumes into job categories.

4. **Prediction & Evaluation**  
   Predict job categories for new resumes and evaluate performance using metrics.

---

## 📊 Sample Output

![Model Accuracy](https://github.com/user-attachments/assets/17f6e079-20f2-4c38-a8bc-96642d4911e0)
![Classification Report](https://github.com/user-attachments/assets/4887a66d-4dcf-4c7c-ad13-8eed32a92eee)

---

## 🔮 Future Improvements
- Use advanced models like SVM, Random Forest, or BERT for improved accuracy.
- Build a web-based interface for real-time resume classification.
- Deploy as an API for integration with HR systems.

---

