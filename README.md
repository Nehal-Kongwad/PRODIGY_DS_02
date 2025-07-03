# 🚢 Titanic Data Analysis – PRODIGY_DS_02

This project performs **Data Cleaning** and **Exploratory Data Analysis (EDA)** on the Titanic dataset from Kaggle, as part of my **Data Science Internship Task** under Prodigy InfoTech.

---

## 📁 Dataset Used

- **File**: `Titanic-Dataset.csv`
- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- The dataset contains information about passengers such as age, sex, ticket class, fare, and whether they survived or not.

---

## 🎯 Objectives

- Handle missing values and clean raw data.
- Convert categorical variables into numerical formats.
- Explore relationships between features and the survival rate.
- Visualize key patterns and trends using plots.

---

## 📊 Exploratory Data Analysis (EDA)

### ➤ Univariate Analysis:
- Distribution of Age, Fare, and Survival count
- Count plots for categorical variables like Sex, Pclass, Embarked

### ➤ Bivariate Analysis:
- Survival by Gender, Class, Age
- KDE plots for survival distribution by Age

### ➤ Correlation:
- Heatmap of correlation matrix among numerical features

---

## 🧹 Data Cleaning Performed

- Filled missing `Age` values using the **median**
- Imputed `Embarked` with the **mode**
- Dropped `Cabin`, `Name`, `Ticket`, and `PassengerId` as irrelevant
- Converted `Sex` and `Embarked` to numeric codes

---

## 🧠 Key Insights

- 💡 **Women** had a significantly higher survival rate than men.
- 💡 **1st Class passengers** had better survival odds.
- 💡 Passengers who embarked from **Cherbourg (C)** had relatively higher survival.
- 💡 Most fatalities occurred among **3rd class male passengers**.

---

## 💻 Technologies Used

- `Python`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Jupyter Notebook`

---



## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Nehal-Kongwad/PRODIGY_DS_02.git
