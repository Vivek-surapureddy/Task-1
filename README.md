
🚢 Titanic Data Cleaning & Preprocessing
📌 Overview
This project is part of an internship task focusing on data cleaning and preprocessing.
The dataset used is the Titanic dataset, which contains passenger information such as age, class, fare, sex, and survival status.

🔧 Workflow
Data Import & Exploration
Loaded the Titanic dataset using Pandas.
Checked data types, shape, and missing values.
Handling Missing Values
Age → filled with median.
Embarked → filled with mode.
Cabin → dropped due to excessive missing values.
Encoding Categorical Variables
Converted Sex and Embarked using One-Hot Encoding.
Feature Scaling
Standardized numerical features (Age, Fare) using StandardScaler.
Outlier Removal
Visualized outliers with boxplots.
Removed extreme values using the IQR method.
Final Output
Saved the cleaned dataset as titanic_cleaned.csv.

📊 Visuals

Heatmap of missing values
Boxplot of Fare (before vs after outlier removal)
Age distribution after preprocessing

🛠 Tech Stack
Python
Pandas, NumPy → data manipulation
Matplotlib, Seaborn → visualization
Scikit-learn → scaling and preprocessing

📂 Repository Layout
📂 Titanic-Preprocessing
 ├── Task1_Data_Cleaning.ipynb   # Notebook with code + explanations
 ├── titanic_cleaned.csv         # Cleaned dataset
 └── README.md                   # Documentation
