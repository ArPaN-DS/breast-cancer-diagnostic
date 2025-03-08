# 🏥 Breast Cancer Diagnostic using R Programming

## 📌 Project Overview
This project implements a **Breast Cancer Diagnostic System** using **R Programming**. It involves data cleaning, exploratory data analysis (EDA), feature selection, **Principal Component Analysis (PCA)**, and **Logistic Regression** for classification.

## 📂 Dataset Information
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/)
- **Description**: The dataset contains medical features extracted from breast cancer cell nuclei.
- **Target Variable**:
  - `B` - Benign
  - `M` - Malignant

## 🛠️ Technologies Used
- **Programming Language**: R
- **Libraries**: 
  - `dplyr`, `ggplot2`, `caret`, `randomForest`, `pROC`

## 🚀 Steps in the Project

### 1️⃣ Load Dataset and Explore Data
- Read dataset from UCI repository.
- Display first few rows and summary statistics.

### 2️⃣ Data Cleaning
- Check for missing values.
- Handle data types and ensure proper formatting.

### 3️⃣ Exploratory Data Analysis (EDA)
- **Boxplots & Histograms**: Analyze distributions of `Radius Mean`, `Texture Mean`, and `Smoothness Mean` for malignant and benign tumors.
- **Scatter Plots**: Visualize feature relationships.

### 4️⃣ Correlation Analysis
- Compute the **correlation matrix** of key features.
- **Visualize using a heatmap**.

### 5️⃣ Malignant vs Benign Analysis
- Perform statistical tests to identify significant variations in features.

### 6️⃣ Feature Selection
- **T-tests** to compare the means of different features between malignant and benign tumors.

### 7️⃣ Principal Component Analysis (PCA)
- Reduce dimensionality using **PCA**.
- Scatter plot of **PC1 vs PC2** to visualize class separation.

### 8️⃣ Logistic Regression Model
- Build a **logistic regression model** for classification.
- Evaluate model using:
  - **Accuracy**
  - **Precision, Recall, F1-score**
  - **ROC Curve & AUC Score**

### 🔥 Model Performance
- **Confusion Matrix**: Evaluate model predictions.
- **AUC-ROC Curve**: Measure classification performance.

## 🎯 Results & Insights
- The **logistic regression model** achieved high accuracy in diagnosing breast cancer.
- The **Random Forest model** (if extended) can be used for further improvement.
- **PCA** helped in feature selection and visualization.

## 🏗️ How to Run the Project
1. Install required R packages:
   ```r
   install.packages(c("dplyr", "ggplot2", "caret", "randomForest", "pROC"))
