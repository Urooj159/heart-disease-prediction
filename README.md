# Heart Disease Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict the presence of heart disease based on patient health-related attributes. A Random Forest classification algorithm is used to classify patients into two categories: heart disease absent or present.

## Project Objectives
- Explore and understand the heart disease dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values.
- Encode categorical features.
- Apply feature scaling.
- Train a Random Forest classification model.
- Evaluate model performance using multiple classification metrics.
- Identify important features influencing model predictions.

## Dataset
**Dataset:** UCI Cleveland Heart Disease Dataset

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)

The dataset contains patient information, including:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Maximum heart rate
- Exercise-induced angina
- Other clinical attributes

The original target values are converted into binary categories:

- `0`: No heart disease
- `1`: Heart disease present

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Methodology

### 1. Data Loading
Loaded the Cleveland Heart Disease dataset using Pandas.

### 2. Exploratory Data Analysis
- Examined dataset structure and statistical information.
- Checked missing and duplicate values.
- Visualized target distribution.
- Created correlation heatmaps and age distribution plots.

### 3. Data Preprocessing
- Removed records with missing target values.
- Handled missing numerical values using median imputation.
- Handled missing categorical values using most-frequent imputation.
- Applied One-Hot Encoding to categorical features.
- Applied StandardScaler to numerical features.

### 4. Model Training
Used the Random Forest Classifier with 200 estimators and a fixed random state.

### 5. Model Evaluation
Evaluated performance using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- Classification Report
- ROC Curve

### 6. Feature Importance
Visualized the most influential features identified by the trained Random Forest model.

## How to Run the Project

1. Open Google Colab.
2. Upload or open `notebook.ipynb`.
3. Run the notebook cells in sequence.
4. The dataset will be downloaded automatically.
5. Review the visualizations and evaluation results.
6. The trained model will be saved as `heart_disease_model.pkl`.

## Project Files

- `notebook.ipynb` – Complete implementation and analysis.
- `README.md` – Project documentation.
- `requirements.txt` – Required Python libraries.

## Results
Actual evaluation metrics are generated when the notebook is executed. No performance values are assumed or hardcoded.

## Disclaimer
This project is developed for educational and research purposes only. It is not a clinically validated diagnostic system and must not be used as a substitute for professional medical advice or diagnosis.

## Author
Developed as part of an Artificial Intelligence and Machine Learning internship.
