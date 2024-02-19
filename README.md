
# Stroke Prediction Model

## Project Overview
This project focuses on predicting the likelihood of a stroke in patients based on various health parameters. The dataset used comprises different attributes like age, gender, hypertension status, heart disease presence, etc., with the goal to train a model that can accurately predict stroke occurrences.

## Data Source
stroke_data.csv provided in the enclosing zip file

## Features
- `id`: Unique patient identifier
- `gender`: Patient's gender
- `age`: Age of the patient
- `hypertension`: Indicates if the patient has hypertension
- `heart_disease`: Indicates if the patient has any heart diseases
- `ever_married`: Marital status of the patient
- `work_type`: Type of occupation
- `Residence_type`: Rural or Urban residence
- `avg_glucose_level`: Average glucose level in blood
- `bmi`: Body Mass Index
- `smoking_status`: Patient's smoking status
- `stroke`: Indicates if the patient had a stroke

## Installation
To set up the project environment, run the following command to install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Open the Jupyter Notebook (`Stroke_Prediction_Model.ipynb`) and run the cells sequentially to see the analysis and model training in action.

## Methodology
- Data exploration and preprocessing.
- Feature engineering and selection.
- Model training using algorithms like Logistic Regression, Random Forest, Gradient Boosting, etc.
- Model evaluation based on metrics such as accuracy, precision, recall, and F1 score.
- Hyperparameter tuning for model optimisation.

## Results
The results so far show a higher performance of logistic regression methodologies when favouring recall.
The Confusion Matrix is as follow:

|                      | Predicted: No | Predicted: Yes |
|----------------------|---------------|----------------|
| **Actual: No**       | 694           | 285            |
| **Actual: Yes**      | 6             | 37             |

Further details are directly in the notebook.


## Contact
- Name: Varin
- Email: geoffreyvarin@hotmail.com
- Project Link: [URL of your project repository, if available]
