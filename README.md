# Stroke Prediction using Machine Learning

Stroke is one of the leading causes of mortality worldwide. Survivors often face long-term health challenges such as paralysis, vision loss, and speech impairments. Early detection can significantly reduce the risk and impact of strokes.  

This project applies Exploratory Data Analysis (EDA), statistical methods, and machine learning techniques to analyze health and lifestyle factors for stroke prediction using the [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  

## Project Overview
- **Objective**: Analyze stroke-related data and build predictive models.  
- **Dataset**: Kaggle Stroke Prediction Dataset (5,110 rows, 12 features).  
- **Techniques Used**:  
  - Exploratory Data Analysis (EDA)  
  - Statistical Analysis  
  - Machine Learning Models: Logistic Regression, Decision Tree, Random Forest  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix  

## Dataset Details
- **Rows**: 5,110  
- **Columns**: 12 (11 features + 1 target)  
- **Target Variable**: `stroke` (0 = No stroke, 1 = Stroke)  
- **Features** include:  
  - Age  
  - Gender  
  - Hypertension  
  - Heart disease  
  - Average glucose level  
  - BMI  
  - Smoking status  
  - Marital status  
  - Work type  
  - Residence type  

## Methods
1. **Data Cleaning & Preprocessing**
   - Handled missing BMI values  
   - Imputed unknown smoking status  
   - Feature engineering (removed unnecessary columns)  
   - Label encoding & min-max scaling  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of categorical & numerical variables  
   - Correlation heatmap  
   - Stroke rate by risk factors (hypertension, heart disease, smoking, etc.)  
   - Outlier analysis on glucose & BMI  

3. **Machine Learning Models**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  

4. **Model Evaluation**
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

## Results and Insights
- **Key Risk Factors**: Age, Hypertension, Heart Disease, High Glucose Levels, Smoking.  
- **Model Performance**: All three models performed with high accuracy.  
- **Limitations**:  
  - Class imbalance (only ~249 stroke cases vs. 4861 non-stroke).  
  - Lack of personalized data (e.g., genetic, stress level, physical activity).  

## Future Work
- Apply SMOTE for class imbalance.  
- Explore Deep Learning techniques (Neural Networks, RNNs).  
- Include personalized and genetic data for better predictions.  
- Use SHAP (Explainable AI) for model interpretability.  
- Validate models in real-world healthcare environments.  


