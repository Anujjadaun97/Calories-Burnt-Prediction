[**Calories Burnt Prediction**](https://github.com/Anujjadaun97/Calories-Burnt-Prediction/blob/main/Calories_Burnt_Prediction.ipynb)


📌 **Project Overview**

This project predicts the number of calories burned during physical activity using demographic and activity-related features. It leverages XGBoost Regressor for regression modeling and evaluates the model’s performance using Mean Absolute Error (MAE).

The dataset was sourced from Kaggle and includes attributes like age, gender, height, weight, duration of activity, and heart rate.
By combining exercise and calorie data, we train a machine learning model to make accurate calorie burn predictions.

📂 **Dataset**

Source: [Kaggle](https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos)

Files Used:

[exercise.csv](https://github.com/Anujjadaun97/Calories-Burnt-Prediction/blob/main/exercise.csv)

[calories.csv](https://github.com/Anujjadaun97/Calories-Burnt-Prediction/blob/main/calories.csv)

**Key Features:**

User_ID

Gender

Age

Height

Weight

Duration (in minutes)

Heart_Rate

Body_Temp

Target Variable: Calories

⚙️ **Steps Performed**

Data Collection

Downloaded the dataset from Kaggle using API.

Extracted and loaded CSV files.

Data Preprocessing

Merged exercise and calories data on User_ID.

Checked for missing values and data types.

Exploratory Data Analysis (EDA)

Distribution plots for age and gender.

Descriptive statistics for numerical features.

Feature Selection & Splitting

Selected relevant features (X) and target (y).

Split dataset into training (80%) and testing (20%).

Model Training

Used XGBoost Regressor to train the model.

Model Evaluation

Measured performance using Mean Absolute Error (MAE).

📊 **Technologies Used**

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Kaggle API

🚀 **How to Run the Project**

Clone the repository:

git clone https://github.com/yourusername/calories-burnt-prediction.git
cd calories-burnt-prediction


Install dependencies:

pip install -r requirements.txt


Add your kaggle.json file for API access in the root directory.

Run the notebook:

jupyter notebook Calories_Burnt_Prediction.ipynb

📈 **Results**

Model Used: XGBoost Regressor

Evaluation Metric: Mean Absolute Error (MAE)

Performance: Low MAE indicates high prediction accuracy.
