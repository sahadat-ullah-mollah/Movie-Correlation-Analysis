# 🎬 Movie Correlation Analysis (Python)

## 📌 Project Overview
This project explores relationships between key movie industry variables using Python. The main focus is to analyze how factors like **budget** influence **gross earnings**, along with other correlations between numerical features in the dataset.

The dataset used is sourced from Kaggle and cleaned for analysis purposes.

🔍 Python File? Check it out here: [Python Project File](https://github.com/Shihab412/Profit_Performance_Analysis_in_Excel/tree/main/Excel%20File)

---

## 🎯 Objectives
- Clean and preprocess raw movie dataset
- Handle missing values and duplicates
- Convert data types for analysis readiness
- Explore correlations between numeric features
- Visualize relationships using plots and heatmaps

---

## 🧰 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Key Analysis Steps

### 1. Data Cleaning
- Removed missing values
- Converted `budget` and `gross` to numeric format
- Extracted correct year from `released` column
- Removed duplicate records

### 2. Exploratory Data Analysis (EDA)
- Budget vs Gross scatter plot
- Regression plot for trend analysis
- Correlation matrix for numeric features

### 3. Feature Engineering
- Converted categorical data (company) into numerical codes
- Generated new feature: `yearCorrect`

### 4. Correlation Analysis
- Pearson correlation used to identify relationships
- Sorted correlation pairs to find strong relationships

---

## 📈 Key Insights
- Strong positive correlation between **budget and gross earnings**
- Certain features show weak or negligible relationships with revenue
- High-budget films tend to generate higher gross income (general trend)

---

## 📷 Visualizations
- Scatter plot: Budget vs Gross <br>

<img width="537" height="530" alt="image" src="https://github.com/user-attachments/assets/ea6ae44e-a080-49a6-8962-bb89f1da6325" /> <br>


- Regression plot: Budget vs Gross

<img width="668" height="452" alt="image" src="https://github.com/user-attachments/assets/6106fd27-fb21-413a-a0f1-b94528a2fc74" /> <br>


- Heatmap: Correlation matrix

<img width="495" height="530" alt="heatmap" src="https://github.com/user-attachments/assets/1bca2b30-9145-4362-ae27-0137ddbebbcc" />


---

## Author

**Sahadat Ullah Mollah**  
Data Analytics Portfolio Project  
[LinkedIn](www.linkedin.com/in/sahadat-ullah)
