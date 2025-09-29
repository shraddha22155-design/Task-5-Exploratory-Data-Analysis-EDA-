
# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Task Overview
This project is part of the **Data Analyst Internship - Task 5**.  
The objective was to perform Exploratory Data Analysis (EDA) on the Titanic dataset and extract meaningful insights using Python.

## 📂 Files in this Repository
- `Titanic_EDA_Task5.ipynb` → Jupyter Notebook with full code and analysis
- `Titanic_EDA_Report.pdf` → PDF report summarizing findings and insights
- `train.csv` → Titanic dataset used for analysis

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

## 📊 Steps Performed
1. **Data Loading & Cleaning**
   - Loaded Titanic dataset (`train.csv`)
   - Checked missing values (`Age`, `Cabin`, `Embarked`)
   - Basic dataset statistics (`.info()`, `.describe()`)

2. **Univariate Analysis**
   - Histograms for `Age` and `Fare`
   - Count plots for `Survived`, `Sex`, and `Pclass`

3. **Bivariate Analysis**
   - Survival vs Gender
   - Survival vs Passenger Class
   - Correlation Heatmap

4. **Insights**
   - Women had much higher survival rates than men
   - First-class passengers had higher survival compared to third-class
   - Younger passengers (20–40 years) were the majority
   - Higher fares were associated with better survival probability
   - Strong negative correlation between `Pclass` and `Survived`

## ✅ Key Takeaways
- **Gender & Class were the most important factors for survival**
- **Fare showed positive correlation with survival**
- **Significant missing data** (Cabin, Age) needs handling for modeling tasks

## 📎 Submission
This repository is ready for submission as per internship guidelines.  
It contains code, dataset, report, and documentation.
