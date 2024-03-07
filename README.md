# Kaggle_Obesity-Classification
Season 4, Episode 2 - Kaggle Playground Series
# 📈🏃‍♀️ Obesity Risk Prediction

## 📝 Description
![image](https://github.com/jha-nikita/Kaggle_Bank-Churn/assets/115389358/c02d6d3f-9c4b-4cf3-a008-8667e6022b20)


- This project aims to predict obesity risk in individuals, based on various factors.
- The prediction is based on various factors provided in the dataset, such as age, gender, family history of overweight, dietary habits, physical activity, and more.

## 📊 Dataset
![image](https://github.com/jha-nikita/Kaggle_Bank-Churn/assets/115389358/799c989e-1a9c-4bb1-8a3c-ca54a490ca16)

- The dataset used for this project is sourced from the Kaggle Playground Series.
- It consists of two CSV files: `train.csv` and `test.csv`.
- **Features** (selected columns from the dataset):
  - '**Gender**': Gender of the individual.
  - '**Age**': Age of the individual.
  - '**family_history_with_overweight**': Family history of overweight.
  - '**FAVC**': Frequency of consuming high-calorie food.
  - '**SMOKE**': Smoking habits.
  - '**SCC**': Calories consumption monitoring.
  - '**CALC**': Consumption of alcohol.
  - '**CAEC**': Consumption of food between meals.
  - '**MTRANS**': Mode of transportation used.
  - Other features include 'Height', 'Weight', 'FCVC', 'NCP', 'CH2O', 'FAF', 'TUE'.
- **Target Variable**:
  - '**NObeyesdad**': Indicates obesity risk.


## 🛠️ Requirements
- Python 3
- Libraries:
  - pandas: For data manipulation and analysis.
  - scikit-learn: For machine learning algorithms and evaluation metrics.
  - GradientBoostingClassifier: For building gradient boosting models.

## ⚙️ Pipeline/Approach

### Data Preprocessing:
- Removed the 'id' column from the dataset.
- Encoded categorical variables using LabelEncoder.
- Scaled numerical features using StandardScaler.

### Model Building:
- Utilized GradientBoostingClassifier as the main predictive model.
- Experimented with hyperparameter tuning using GridSearchCV and RandomizedSearchCV to optimize model performance.

### Model Evaluation:
- Evaluated model performance using accuracy score on the validation set.


## 🚀 Usage
1. Clone the repository:

```bash
git clone https://github.com/jha-nikita/Kaggle_Obesity-Classification

## 📝 Credits

- [Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s4e2/overview)
- [Dataset Source](https://www.kaggle.com/competitions/playground-series-s4e2/data)
