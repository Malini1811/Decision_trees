# Heart Disease Prediction using Decision Tree & Ensemble Methods

## Project Overview

This project focuses on predicting the presence of heart disease using machine learning models like **Decision Tree** and **Ensemble Methods** such as **Random Forest**, **Gradient Boosting** and **XGBoost**.

## Files Included

1. **Decision_tree & ensemble_methods.ipynb**  
   - A Jupyter Notebook containing:
     - Exploratory Data Analysis (EDA)
     - Preprocessing steps
     - Training and evaluation of models (Decision Tree, Random Forest, etc.)
     - Model performance comparison

2. **heart.csv**  
   - The dataset used for training and testing models.
   - Contains **303 rows** and **14 columns**.

## Dataset Columns

- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (0 to 3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0 to 2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy (0–3)
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- `target`: Diagnosis of heart disease (1 = disease, 0 = no disease)

## Sample Data

```
age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target
63,   1,   3,  145,      233,  1,   0,       150,     0,     2.3,     0,     0,   1,    1
37,   1,   2,  130,      250,  0,   1,       187,     0,     3.5,     0,     0,   2,    1
41,   0,   1,  130,      204,  0,   0,       172,     0,     1.4,     2,     0,   2,    1
```

## Objective

To compare different machine learning models and identify the best-performing one for predicting heart disease based on medical data.

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

