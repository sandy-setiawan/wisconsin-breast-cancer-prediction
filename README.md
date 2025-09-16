# Wisconsin Breast Cancer Classification

## 📌 Project Overview
This project applies **Logistic Regression** to the **Wisconsin Breast Cancer (Diagnostic) Dataset**, a well-known dataset in the machine learning community. The goal is to build a predictive model that can classify breast cancer tumors as either **malignant (cancerous)** or **benign (non-cancerous)** based on cell nuclei features computed from digitized images of breast tissue.

---

## 📊 Dataset
- **Source:** Built-in dataset from [Scikit-learn](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)  
- **Samples:** 569  
- **Features:** 30 numeric features derived from 10 real-valued measurements of cell nuclei (mean, standard error, and worst values).  
- **Target classes:**
  - `0 = malignant`  
  - `1 = benign`  

---

## ⚙️ Methodology
1. Load dataset using `sklearn.datasets.load_breast_cancer()`.  
2. Preprocess data (split into training and testing sets).  
3. Train a **Logistic Regression** classifier.  
4. Evaluate model performance on both training and testing sets.  

---

## 📈 Results
- **Training Accuracy:** 94.95%  
- **Testing Accuracy:** 95.61%  

These results indicate that the Logistic Regression model generalizes well and performs reliably in classifying tumors.

---

## 📌 Dependencies
- Python 3.8+  
- scikit-learn  
- numpy
- pandas  
- matplotlib
- seaborn

---

## ✅ Conclusion
The Logistic Regression model achieves strong performance on the Wisconsin Breast Cancer dataset, with over **95% accuracy** on the test set. This project demonstrates the effectiveness of Logistic Regression in solving binary classification problems in medical diagnostics.
