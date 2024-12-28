# Heart Disease Prediction Model

## Overview
This repository contains a machine learning model built using the Scikit-learn library to predict heart disease based on clinical features. The dataset used is the Heart Disease dataset, and the project demonstrates data preprocessing, exploratory data analysis, and model training.

## Features
The dataset includes the following key features:
- **Age**: Age of the patient
- **Sex**: Gender (1 = Male, 0 = Female)
- **Chest Pain Type**: Types of chest pain (e.g., typical angina, atypical angina, etc.)
- **Resting Blood Pressure**: Measured in mm Hg
- **Cholesterol**: Serum cholesterol in mg/dl
- **Fasting Blood Sugar**: > 120 mg/dl (1 = True, 0 = False)
- **Resting ECG**: Results of resting electrocardiographic tests
- **Max Heart Rate Achieved**: Maximum heart rate during exercise
- **Exercise-Induced Angina**: (1 = Yes, 0 = No)
- **ST Depression**: Exercise-induced depression in ST segment

## Project Workflow
1. **Data Loading**
   - The dataset is loaded into a Pandas DataFrame.
2. **Data Preprocessing**
   - Handling missing values.
   - Encoding categorical features.
   - Scaling numerical features.
3. **Exploratory Data Analysis**
   - Visualization of feature distributions.
   - Correlation analysis.
4. **Model Building**
   - Training a machine learning model (e.g., Logistic Regression, Random Forest).
   - Hyperparameter tuning.
5. **Evaluation**
   - Metrics like accuracy, precision, recall, and ROC-AUC are used to evaluate performance.

## Dependencies
- Python 3.8+
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd heart_disease_prediction
   ```
3. Run the Jupyter notebook to see the implementation step-by-step.

## Results
- The trained model achieves an accuracy of X% on the test dataset.
- Key insights from feature importance:
  - Features like age, cholesterol, and max heart rate are critical predictors.

## Future Improvements
- Add more advanced models like XGBoost or Neural Networks.
- Deploy the model as a web application using Flask or FastAPI.
- Include a larger and more diverse dataset.

## Author
- Hir Shah

Feel free to raise issues or contribute to the repository!
