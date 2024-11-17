# **Supervised Learning: Breast Cancer Classification**

This project is part of a formative assessment to demonstrate supervised learning techniques using the breast cancer dataset from the `sklearn` library. The project involves implementing multiple classification algorithms, comparing their performance, and drawing insights from the results.

## **Objective**
To evaluate the performance of various supervised learning models on the breast cancer dataset and identify the most suitable model for the task.

---

## **Dataset**
The dataset is the Breast Cancer dataset available in the `sklearn.datasets` library.  
- **Features**: 30 numeric features describing characteristics of cell nuclei.
- **Target**: Binary classification — malignant (0) or benign (1).

---

## **Key Components**

### **1. Loading and Preprocessing**
- Loaded the dataset using `sklearn.datasets.load_breast_cancer`.
- Checked for missing values and scaled features using `StandardScaler` to ensure uniform feature importance.
- Split the dataset into training and testing sets (80%-20% split).

### **2. Classification Algorithms**
Implemented the following supervised learning models:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**
5. **k-Nearest Neighbors (k-NN)**

### **3. Model Comparison**
- Evaluated each model using metrics such as **accuracy, precision, recall**, and **F1-score**.
- Visualized model performance through a bar plot.
- Identified the best and worst-performing algorithms.

---

## **Results**

- **Best Model**: Identified the algorithm with the highest accuracy and balanced performance.
- **Worst Model**: Highlighted the algorithm with the lowest performance and explained potential reasons.

---

## **Setup and Usage**

1. Clone the repository:
   ```bash
  https://github.com/fyzl04/breast-cancer-classification/
