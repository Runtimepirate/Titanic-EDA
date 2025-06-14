# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📁 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset. The goal is to uncover patterns in passenger demographics, survival distribution, missing values, and relationships between variables. This EDA uses visualizations to provide insights into the underlying structure of the dataset and the factors that may have influenced survival outcomes.

---

## 📌 Dataset Information

- **Source:** [Titanic Dataset (GitHub - Data Science Dojo)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Format:** CSV
- **Total Rows:** 891 passengers
- **Total Columns:** 12 attributes including survival status, class, age, sex, fare, and more.

### Column Overview:

- `PassengerId` – ID given to each traveler on the Titanic
- `Survived` – Survival status (0 = No, 1 = Yes)
- `Pclass` – Passenger class (1st, 2nd, 3rd)
- `Name`, `Sex`, `Age` – Demographic information
- `SibSp`, `Parch` – Family relationships aboard
- `Ticket`, `Fare` – Ticket number and cost
- `Cabin`, `Embarked` – Cabin and embarkation port

---

## 🎯 Objectives

- Understand feature distributions using histograms and countplots.
- Identify and visualize missing values.
- Detect outliers in numerical data using boxplots.
- Analyze survival rates across different passenger segments.
- Explore correlations between variables using a heatmap.

---

## 🛠️ Tools and Libraries Used

- Python 3
- pandas
- numpy
- matplotlib
- seaborn

---

## 📌 Key Insights

- **Gender:** Female passengers had a much higher survival rate than males.
- **Class:** Passengers in 1st class had significantly better survival chances.
- **Age:** Young children had relatively better survival rates. The age feature had missing values.
- **Fare:** Some extreme outliers were observed in the fare distribution.
- **Missing Values:** Columns like `Age`, `Cabin`, and `Embarked` contain missing values.
- **Embarkation Port:** Passengers who embarked from port 'C' had higher chances of survival.

---

## 📈 Visualizations Used

- **Histograms:** For distributions of Age and Fare
- **Countplots:** For categorical variables like Sex, Pclass, Embarked
- **Boxplots:** To detect outliers in Age and Fare
- **KDE Plot:** Age distribution by survival
- **Heatmap:** Missing values and correlation matrix

---

## 📬 How to Run the Project

1. Download or clone the repository.
2. Make sure you have the required libraries:  pip install pandas matplotlib seaborn
3. Open the `titanic_eda.ipynb` file in Jupyter Notebook or Google Colab.
4. Run all cells to explore the dataset and view the visualizations.

---

## 📝 License & Credits

- Dataset provided by [Data Science Dojo](https://github.com/datasciencedojo/datasets).
- Analysis conducted as part of academic assignment by *Aditya Katariya*.
