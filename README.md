# ❤️ Heart Disease Analysis Using Python

## 📌 Project Overview

The **Heart Disease Analysis** project focuses on analyzing health-related data to identify patterns and factors associated with heart disease. Python libraries are used for data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization.

The project explores how factors such as age, BMI, smoking, diabetes, physical activity, general health, and sleep duration are associated with heart disease.

## 🎯 Project Objectives

* Understand the dataset and its features.
* Clean and preprocess the data.
* Perform exploratory data analysis (EDA).
* Analyze relationships between health factors and heart disease.
* Create meaningful visualizations.
* Identify key findings and provide practical health recommendations.

## 📂 Dataset Information

* **Dataset:** Heart Disease Dataset
* **Source:** [Zenodo Dataset](https://zenodo.org/records/15336526)
* **Original records:** 319,795
* **Original columns:** 18
* **Data type:** Structured health-related data

### Key Features

* `HeartDisease` – Heart disease status
* `BMI` – Body Mass Index
* `Smoking` – Smoking history
* `AlcoholDrinking` – Alcohol consumption status
* `Stroke` – History of stroke
* `PhysicalHealth` – Number of days with poor physical health
* `MentalHealth` – Number of days with poor mental health
* `Sex` – Sex of the respondent
* `AgeCategory` – Age group
* `Diabetic` – Diabetes status
* `PhysicalActivity` – Physical activity status
* `GenHealth` – General health condition
* `SleepTime` – Average sleep duration
* `Asthma` – Asthma status
* `KidneyDisease` – Kidney disease status
* `SkinCancer` – Skin cancer status

## 🛠️ Tools and Technologies

* **Python** – Data analysis
* **Google Colab** – Notebook development
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualizations

## 🔍 Project Workflow

### 1. Data Loading and Overview

* Imported the dataset using Pandas.
* Examined the number of rows and columns.
* Checked data types and statistical summaries.

### 2. Data Cleaning and Preprocessing

* Checked for missing values and duplicate records.
* Removed duplicate records.
* Reviewed data types and data consistency.
* Created a new feature, `BMI_Category`.
* Retained BMI outliers for analysis rather than removing them automatically.

### 3. Exploratory Data Analysis (EDA)

* Performed univariate analysis to understand individual variables.
* Performed bivariate analysis to compare health factors with heart disease.
* Used groupby operations, cross-tabulations, and correlation analysis.
* Examined numerical and categorical variables.

### 4. Data Visualization

Created visualizations to explore:

* Heart disease distribution
* Heart disease prevalence across age groups
* BMI category distribution
* Smoking and heart disease
* Diabetes and heart disease
* General health and heart disease
* Physical activity and heart disease
* Sleep duration and heart disease
* Relationships between numerical health variables

### 5. Insights and Recommendations

Summarized the important patterns found during the analysis and identified areas that may deserve further investigation.

## 📊 Key Findings

* Approximately **9.04%** of the analyzed records reported heart disease.
* The **80+ age group** had the highest observed heart disease prevalence among the age groups analyzed.
* The obesity category had a higher observed heart disease prevalence (**10.62%**) than the normal BMI category (**6.92%**).
* Participants with a smoking history had a higher observed prevalence (**12.54%**) than those without a smoking history (**6.47%**).
* Participants reporting diabetes had a higher observed prevalence (**22.05%**) than those without diabetes (**6.92%**).
* Participants reporting poor general health had a higher observed prevalence (**34.11%**) than those reporting excellent general health (**2.50%**).
* Participants reporting no physical activity had a higher observed prevalence (**13.86%**) than those reporting physical activity (**7.54%**).

## **Insight**

The analysis highlights heart disease patterns across age groups and health conditions. It identifies associations with factors such as smoking, diabetes, BMI, and physical activity. The findings help identify groups with higher observed heart disease prevalence and support early risk awareness. Practical recommendations include regular health check-ups, physical activity, healthy eating, and effective management of existing health conditions.



## 💡 Recommendations

* Encourage regular health check-ups, especially for older adults and people with existing health conditions.
* Promote physical activity and healthy lifestyle habits.
* Support smoking cessation and diabetes management.
* Encourage appropriate weight management and balanced nutrition.
* Use these findings as a starting point for further research, not as a substitute for medical advice.



## 🏁 Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize health-related data. The analysis identified differences in observed heart disease prevalence across age groups, BMI categories, smoking status, diabetes status, general health, and physical activity. These findings can help guide further investigation into factors associated with heart disease.

## 👩‍💻 Author

**Suganya**
Aspiring Data Analyst
