# Heart Attack Prediction Dataset

## General Description
This dataset is designed to predict the risk of heart attacks based on clinical and demographic variables. This dataset provides a comprehensive range of features relevant to heart health and lifestyle choices, covering patient-specific details such as age, gender, cholesterol levels, blood pressure, heart rate, and more. The dataset culminates in a crucial binary classification feature that indicates the presence or absence of a heart attack risk, providing a comprehensive resource for predictive analytics and cardiovascular health research.

- **Source**: [Kaggle -Heart Attack Risk Prediction Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data)
- **Archive**: `heart_attack_prediction_dataset.csv`
- **Lines**: 8763
- **Columns**: 26
- **Format**: CSV
- **Observation**: Data collected from different regions of the world.

## Column Structure

| Column                            | Type   | Description                                                             |
|---------------------|----------------------|-------------------------------------------------------------------------|
| `Patient ID`                      | object |  Unique identifier for each patient                                     |
| `Age`                             | Int    |  Age of the patient                                                     |
| `Sex`                             | object |  Gender of the patient (Male/Female)                                    |
| `Cholesterol`                     | int    |  Cholesterol levels of the patient                                      |
| `Blood Pressure`                  | object |  Blood pressure of the patient (systolic/diastolic)                     |
| `Heart Rate`                      | int    |  Heart rate of the patient.                                             |
| `Diabetes`                        | int    |  Whether the patient has diabetes (Yes/No).                             |
| `Family History`                  | int    |  Family history of heart-related problems (1: Yes, 0: No)               |
| `Smoking`                         | int    |  Smoking status of the patient (1: Smoker, 0: Non-smoker).              |
| `Obesity`                         | int    |  Obesity status of the patient (1: Obese, 0: Not obese).                |
| `Alcohol Consumption`             | int    |  Level of alcohol consumption by the patient(None/Light/Moderate/Heavy) |
| `Exercise Hours Per Week`         | float  |  Number of exercise hours per week                                      |
| `Diet`                            | object |  Dietary habits of the patient (Healthy/Average/Unhealthy).             |
| `Previous Heart Problems`         | int    |  Previous heart problems of the patient (1: Yes, 0: No) .               |
| `Medication Use`                  | int    |  Medication usage by the patient (1: Yes, 0: No)                        |
| `Stress Level`                    | int    |  Stress level reported by the patient (1-10).                           |
| `Sedentary Hours Per Day`         | float  |  Hours of sedentary activity per day                                    |
| `Income`                          | int    |  Income level of the patient                                            |
| `BMI`                             | float  |  Body Mass Index (BMI) of the patient                                   |
| `Triglycerides`                   | int    |  Triglyceride levels of the patient                                     |
| `Physical Activity Days Per Week` | int    |  Days of physical activity per week                                     |
| `Sleep Hours Per Day`             | int    |  Hours of sleep per day                                                 |
| `Country`                         | object |  Country of the patient                                                 |   
| `Continent`                       | object |  Continent where the patient resides                                    |
| `Hemisphere`                      | object |  Hemisphere where the patient resides                                   |
| `Heart Attack Risk`               | int    |  Presence of heart attack risk (1: Yes, 0: No)                          |

## Missing Values
There are no missing values ​​in the dataset.

## Data Content
- **Heart attack risk distribution**:
  - 34% patients are at risk of heart attack.
  - 66% patients who are not at risk of heart attack.


