# 📊 Diabetes Prediction using SVM

## 🚀 Project Overview
This project aims to predict diabetes in patients using machine learning techniques. The **PIMA Diabetes dataset** is analyzed, preprocessed, and modeled using **Support Vector Machine (SVM)** for classification.

## 📂 Dataset
- **Source:** PIMA Diabetes Dataset
- **Attributes:** Includes medical measurements such as glucose levels, insulin, BMI, age, and more.
- **Target Variable:** Binary classification (Diabetic: 1, Non-Diabetic: 0)

## 🔧 Installation
To run this project locally, install the required dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 📜 Data Preprocessing
- **Handled Missing Values** (if any)
- **Feature Scaling** using `StandardScaler`
- **Train-Test Split** (80-20 ratio)

## 🏗️ Model Implementation
- **Algorithm Used:** Support Vector Machine (SVM)
- **Evaluation Metrics:** Accuracy Score, Confusion Matrix


## 📌 Usage
To run this project from **GitHub**, follow these steps:
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook code.ipynb
   ```
4. **Execute Each Cell to Train & Evaluate the Model**

## 📸 Step-by-Step Workflow
1. **Load the Dataset** 📂  
   - Dataset is loaded into a Pandas DataFrame.
   - Displays the first few rows for inspection.
2. **Perform Data Cleaning & Scaling** 🔄  
   - Missing values (if any) are handled.
   - Features are scaled using StandardScaler.
3. **Train the Model** 🤖  
   - Support Vector Machine (SVM) is trained on the dataset.
   - Data is split into training and testing sets.
4. **Evaluate Performance** 📊  
   - Accuracy and confusion matrix are calculated.
   - Model performance is analyzed.

## 🤝 Contributing
Feel free to contribute by raising issues or submitting PRs.


