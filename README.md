# diabetes-risk-classification
Classification-based predictive analytics project for diabetes risk using ML models (Logistic Regression, Decision Tree, Naïve Bayes, Ensemble Learning).

# 🩺 Diabetes Risk Prediction using ML Classification

This project applies predictive analytics and classification models to predict the presence or absence of diabetes based on clinical input data. It explores individual models like Logistic Regression, Naïve Bayes, and Decision Trees, as well as a hybrid ensemble approach.

## 📘 Dataset

- Dataset based on anonymised medical records for classification (binary outcome: diabetes/no diabetes)
- Includes features such as age, BMI, glucose levels, blood pressure, and insulin

## 🧠 Models Implemented

- SVM  
- Random Forest  
- Decision Tree Classifier  
- **Stacking Ensemble**: Combines outputs from all three to boost performance

## 📈 Results Summary

| Model                  | Accuracy (%) |
|------------------------|--------------|
| Random Forest          | 74.6%        |
| SVM                    | 76.0%        |
| Random Forest w SMOTE  | 69.5.9%      |
| SVM w SMOTE            | 76.8%        |
| **Ensemble Model**     | **85.7%**    |

> Ensemble learning via stacking outperformed all individual models in prediction accuracy.

## 🛠️ Tools & Libraries

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib & Seaborn

## 🧪 Key Methods

- Feature scaling and normalisation  
- Stratified training/testing split (80/20)  
- Performance evaluation: accuracy, precision, recall, F1 score  
- Confusion matrix analysis

## 📂 Project Structure

diabetes-risk-classification/  
│  
├── diabetes_prediction.ipynb  
├── requirements.txt  
└── README.md  

  
## 📄 Academic Context

- Created for the course **DS550 – Predictive Analytics**  
- Saudi Electronic University

## 👩‍💻 Author

Madawi Alsoyohi  
[LinkedIn](https://www.linkedin.com/in/madawi-alsoyohi-7134951a6) | [GitHub](https://github.com/madawi84)  
Raghad Alfhaid
