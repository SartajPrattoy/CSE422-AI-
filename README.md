# Heart Disease Prediction using Machine Learning

This project was developed as part of the **CSE422 - Artificial Intelligence coursework**. It focuses on predicting the likelihood of heart disease using various machine learning models. By leveraging clinical and demographic features from the UCI Cleveland Heart Disease Dataset, the project explores data preprocessing, feature engineering, model training, and performance evaluation to determine the most effective approach for heart disease prediction.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Results](#models-and-results)
- [Key Features](#key-features)
- [Impact](#impact)
- [Contributing](#contributing)

## 🎯 Project Overview

This machine learning project aims to predict heart disease using clinical and demographic features. The project implements and compares multiple machine learning algorithms to identify the most effective approach for early heart disease detection.

### Course Context
Developed as a comprehensive project for the **CSE422 Artificial Intelligence course**.

## 📊 Dataset

- **Source:** UCI Cleveland Heart Disease Dataset (sourced via Kaggle)
- **Features:** 14 clinical and demographic attributes
- **Target:** Binary classification (heart disease presence/absence)
- **Size:** 1,028 records

## 📁 Project Structure

```
CSE422_ML_Project/
├── CODE/
│   └── heart_disease_prediction.ipynb    # Main analysis notebook
├── DATA/
│   └── heart_disease_data.csv           # Dataset
└── Report/
    └── Heart_Disease_Prediction_Report.docx    # Detailed project report
```

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SartajPrattoy/CSE422-AI-.git
   cd CSE422-AI-
   ```

2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open the analysis notebook:**
   Navigate to `CSE422_ML_Project/CODE/heart_disease_prediction.ipynb`

## 💻 Usage

1. **Data Loading and Exploration:**
   - Load the heart disease dataset
   - Perform exploratory data analysis
   - Visualize data patterns and distributions

2. **Data Preprocessing:**
   - Handle missing values
   - Encode categorical variables
   - Apply feature scaling

3. **Model Training and Evaluation:**
   - Train multiple ML models
   - Compare performance metrics
   - Generate visualizations

4. **Results Analysis:**
   - Analyze model performance
   - Identify best-performing algorithm
   - Generate insights

## 🏆 Models and Results

### Algorithms Implemented
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**
- **Logistic Regression**

### Performance Metrics
- Accuracy
- Precision
- Recall
- F1 Score

### Results Summary
The **Decision Tree model** achieved the highest accuracy of **95.93%**, demonstrating its strength in capturing complex relationships in the data. Logistic Regression followed with decent performance, while SVM and KNN had comparatively lower accuracies.

## ✨ Key Features

- **Comprehensive Data Analysis:** Thorough exploration of data preprocessing, including handling null values, encoding categorical variables, and feature scaling
- **Multiple Algorithm Comparison:** Side-by-side comparison of four different machine learning algorithms
- **Detailed Visualizations:** Rich visualizations of results and data patterns
- **Performance Evaluation:** In-depth analysis using multiple evaluation metrics
- **Healthcare Focus:** Insightful analysis of heart disease risk factors through machine learning lens

## 🌟 Impact

This project showcases the application of machine learning in healthcare for early detection of heart disease. It contributes to:

- **Academic Understanding:** Demonstrates practical application of ML techniques in healthcare
- **Clinical Insights:** Provides valuable insights for healthcare professionals
- **Research Foundation:** Offers a foundation for further research in medical ML applications
- **Policy Implications:** Supports data-driven healthcare decision making

## 🤝 Contributing

This project was developed for academic purposes. For questions or suggestions, please contact the project maintainer.

---

**Note:** This project is part of academic coursework and is intended for educational purposes. For detailed analysis and methodology, refer to the project documentation in the `Report/` directory.

## 📞 Contact

For any questions regarding this project, please refer to the project documentation or contact through the course channels.
