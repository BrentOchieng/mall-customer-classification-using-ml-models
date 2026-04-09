# Mall Customer Segmentation & Classification

## Overview
This project applies machine learning techniques to analyze and classify mall customers based on their demographics and spending behavior.

The goal is to predict customer segments using multiple models and compare their performance.

---
- LINK TO THE NOTEBOOK: https://nbviewer.org/github/BrentOchieng/mall-customer-classification-using-ml-models/blob/main/mall_customer_classification.ipynb
---

##  Objectives
- Perform Exploratory Data Analysis (EDA)
- Build classification models
- Compare model performance
- Visualize predictions
- Create a clean ML pipeline

---

##  Dataset
The dataset contains customer information such as:
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Models Used
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

##  Workflow

### 1. Data Loading
- Imported dataset using Pandas

### 2. Data Preprocessing
- Selected relevant features
- Split into training and testing sets
- Applied feature scaling

### 3. Model Training
- Trained three different models:
  - Decision Tree
  - Random Forest
  - SVM

### 4. Model Evaluation
- Used classification report
- Compared model performance

### 5. Predictions
- Generated predictions on new/unseen data
- Combined predictions into a structured DataFrame

### 6. Visualization
- Compared model outputs using histograms

---

## Results & Insights
- Decision Tree performed best.
- SVM performed well after scaling
- Random Forest was interpretable but prone to overfitting

---

## How to Run the Project

```bash
# Clone the repository
git clone https://github.com/BrentOchieng/mall-customer-classification.git

# Navigate into the folder
cd mall-customer-classification

# Install dependencies
pip install -r requirements.txt

# Run the notebook
