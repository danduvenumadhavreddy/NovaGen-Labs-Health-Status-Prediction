# NovaGen-Labs-Health-Status-Prediction
A machine learning project that analyzes health indicators and lifestyle-related features to classify health-status labels using Logistic Regression, Decision Trees, and Random Forest.
# NovaGen Labs – Health Status Prediction

## Overview
NovaGen Labs is a machine learning project that explores health-related indicators and lifestyle data to classify health-status labels. It applies exploratory data analysis, feature correlation analysis, and supervised classification algorithms to study patterns in the dataset.

## Objectives
- Explore health indicators and lifestyle-related features.
- Inspect missing values and target-class distribution.
- Analyze correlations between input features and the target.
- Train and compare classification models.
- Evaluate model performance using classification metrics.
- Explore Decision Tree complexity and cost-complexity pruning.

## Dataset
- **Records:** 9,549
- **Columns:** 23, including 22 input features and 1 target variable
- **Target variable:** `Target`
- **Problem type:** Binary classification

### Features
The dataset includes:
- **Health indicators:** Age, BMI, blood pressure, cholesterol, glucose level, and heart rate.
- **Lifestyle indicators:** Sleep hours, exercise hours, water intake, and stress level.
- **Additional attributes:** Smoking, alcohol, diet, mental health, physical activity, medical history, allergies, diet type, and blood-group indicators.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Exploratory Data Analysis
- Inspected dataset structure and missing values.
- Examined the target-class distribution.
- Visualized feature correlations using a heatmap.
- Ranked features by their correlation with the target variable.

## Machine Learning Workflow
1. Load and inspect the dataset.
2. Examine missing values and target distribution.
3. Encode selected categorical and Boolean features.
4. Perform correlation analysis.
5. Prepare input features and the target variable.
6. Split the dataset into training and testing sets.
7. Apply StandardScaler to the training and testing features.
8. Train a Logistic Regression classifier.
9. Train and visualize a Decision Tree classifier.
10. Explore cost-complexity pruning using `ccp_alpha`.
11. Train a Random Forest classifier and evaluate its performance.

## Machine Learning Algorithms
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Model Evaluation
The notebook uses:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Out-of-bag (OOB) score for Random Forest

## Repository Structure
```text
NovaGen-Health-Status-Prediction/
├── NovaGen_Labs.ipynb
├── novagen_dataset.csv
└── README.md
```

## How to Run
1. Clone or download this repository.
2. Install the dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Ensure the CSV file is in the same directory as the notebook.
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook NovaGen_Health_Status_Prediction.ipynb
   ```
5. Run the notebook cells in sequence.

## Disclaimer
This is an educational machine learning project. Its outputs are not medical diagnoses and should not be used to make healthcare decisions.
