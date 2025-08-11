# 🚢 Titanic - Exploratory Data Analysis (EDA)

## 📌 Overview
This project analyzes the Titanic dataset using Python and Jupyter Notebook to uncover patterns in passenger survival. It involves data cleaning, visualization, and extracting key insights from the dataset.

## 📂 Dataset Description
The dataset contains passenger details from the Titanic disaster, including:
- **PassengerId** – Unique ID for each passenger
- **Pclass** – Ticket class (1st, 2nd, 3rd)
- **Name** – Passenger's full name
- **Sex** – Gender
- **Age** – Age in years
- **SibSp** – Number of siblings/spouses aboard
- **Parch** – Number of parents/children aboard
- **Ticket** – Ticket number
- **Fare** – Passenger fare
- **Cabin** – Cabin number
- **Embarked** – Port of embarkation
- **Survived** – Survival status (0 = No, 1 = Yes) *(only in train set)*

Files included:
- `train.csv`
- `test.csv`
- `gender_submission.csv`

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

## 🛠 Tools & Libraries Used
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Steps in the Analysis
1. **Load Data** – Read CSV files into Pandas DataFrames.
2. **Understand Data** – Use `.info()`, `.describe()`, and `.head()` to explore.
3. **Data Cleaning** – Handle missing values and correct data types.
4. **Exploratory Analysis** – Analyze relationships between survival and features.
5. **Visualization** – Create plots for survival rates by gender, class, and age.
6. **Insights Extraction** – Summarize findings from visualizations.

## 📈 Key Insights
- **Women** had a much higher survival rate compared to men.
- **1st class** passengers had the highest chance of survival.
- **Younger** passengers were more likely to survive.
- **Fare price** had a positive correlation with survival.
- Passengers embarking from **Cherbourg** had higher survival rates.

## 🚀 How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Titanic.git
   
2.Navigate to the folder:
cd Titanic

3.Install dependencies:
pip install pandas matplotlib seaborn jupyter

4.Open and run the notebook:

jupyter notebook Task-5.ipynb

📎 Files in This Project
Task-5.ipynb → Jupyter Notebook with analysis

Task-5 → PDF version of the notebook

train.csv, test.csv, gender_submission.csv → Dataset files

