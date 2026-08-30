## Week:1 ML Fundamentals & Data Preprocessing

## Mini Project: Titanic Survival Prediction – Data Cleaning Project

### Objective

The objective of this project is to understand basic machine learning concepts and perform data preprocessing using the Titanic dataset.

### Tasks Completed

- Loaded the Titanic dataset using Pandas
- Explored the dataset using `info()` and `describe()`
- Checked missing values
- Handled missing `Age` values using median imputation
- Handled missing `Embarked` values using mode imputation
- Removed the `Cabin` column because of excessive missing values
- Encoded `Sex` using LabelEncoder
- Encoded `Embarked` using OneHotEncoder
- Visualized age distribution using Matplotlib and Seaborn
- Performed Train/Test Split
- Exported the cleaned dataset as a CSV file

### Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Files

- `Week1_Titanic_Data_Preprocessing.ipynb` – Complete Jupyter Notebook
- `titanic_cleaned.csv` – Cleaned Titanic dataset
- `README.md` – Project documentation


---

## Week 2: Logistic Regression – Titanic Survival Prediction

### Objective

The objective of this task is to train a Logistic Regression model
on the cleaned Titanic dataset to predict passenger survival.

### Tasks Completed

- Loaded the cleaned Titanic dataset
- Selected relevant features for prediction
- Selected `Survived` as the target variable
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Predicted passenger survival
- Evaluated the model using accuracy
- Created a confusion matrix

### Model Performance

- Model: Logistic Regression
- Accuracy: 81.01%

### Files

- `Week1_Titanic_Data_Preprocessing.ipynb` – Complete data preprocessing notebook
- `titanic_cleaned.csv` – Cleaned Titanic dataset
- `Titanic_Logistic_Regression.ipynb` – Week 2 Logistic Regression notebook
- `README.md` – Project documentation
