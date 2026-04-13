# Spam Email Classifier using Machine Learning

## 📌 Overview
This project builds a machine learning model to classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

---

## 🎯 Objectives
- Perform text preprocessing
- Convert text data into numerical features
- Train classification models
- Compare model performance
- Evaluate using multiple metrics
- Ensure robustness using cross-validation

---

## 📂 Dataset
- SMS Spam Collection Dataset
- Contains labeled messages:
  - **Spam (1)** → unwanted messages
  - **Ham (0)** → normal messages

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## ⚙️ Workflow
1. Load and clean dataset  
2. Convert labels (ham = 0, spam = 1)  
3. Split data into training and testing sets  
4. Convert text to numerical features using:
   - CountVectorizer
   - TF-IDF Vectorizer  
5. Train models:
   - Multinomial Naive Bayes  
   - Logistic Regression  
6. Evaluate models using:
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
7. Apply 5-fold cross-validation  
8. Test model with custom input  

---

## 📊 Results
- Accuracy (CountVectorizer): ~98%  
- Accuracy (TF-IDF): ~96–97%  
- Logistic Regression slightly outperformed Naive Bayes  
- Cross-validation accuracy: ~98%  

---

## 🔍 Key Insights
- Text vectorization plays a critical role in model performance  
- Logistic Regression captures feature relationships better than Naive Bayes  
- Cross-validation confirms model stability  
- Model successfully identifies spam messages with high accuracy  

---

## 💡 Example Prediction
Input: "Congratulations! You won a free prize"
Output:Spam


---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Use advanced NLP models (e.g., LSTM, Transformers)  
- Deploy as a web application (Streamlit)  

---

## 👨‍💻 Author
Lahiru
