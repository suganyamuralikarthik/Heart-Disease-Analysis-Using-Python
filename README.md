# ❤️ Heart Disease Analysis Using Python

## 📌 Project Overview

The **Heart Disease Analysis** project focuses on analyzing health-related data to identify patterns and factors associated with heart disease. Python libraries are used for data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

The project explores how factors such as age, BMI, smoking, diabetes, physical activity, general health, and sleep duration are associated with heart disease.

## 🎯 Project Objectives

* Understand the dataset and its features.
* Clean and preprocess the data.
* Perform exploratory data analysis (EDA).
* Analyze relationships between health factors and heart disease.
* Apply statistical techniques to understand significant differences.
* Create meaningful visualizations.
* Identify key findings and provide practical health recommendations.

## 📂 Dataset Information

* **Dataset:** Heart Disease Dataset
* **Source:** [Zenodo Dataset](https://zenodo.org/records/15336526)
* **Original Records:** 319,795
* **Original Columns:** 18
* **Data Type:** Structured health-related data

### Key Features

| Column           | Description                              |
| ---------------- | ---------------------------------------- |
| HeartDisease     | Heart disease status                     |
| BMI              | Body Mass Index                          |
| Smoking          | Smoking history                          |
| AlcoholDrinking  | Alcohol consumption status               |
| Stroke           | History of stroke                        |
| PhysicalHealth   | Number of days with poor physical health |
| MentalHealth     | Number of days with poor mental health   |
| DiffWalking      | Difficulty walking                       |
| Sex              | Sex of the respondent                    |
| AgeCategory      | Age group                                |
| Race             | Race category                            |
| Diabetic         | Diabetes status                          |
| PhysicalActivity | Physical activity status                 |
| GenHealth        | General health condition                 |
| SleepTime        | Average sleep duration                   |
| Asthma           | Asthma status                            |
| KidneyDisease    | Kidney disease status                    |
| SkinCancer       | Skin cancer status                       |

## 🛠️ Tools and Technologies

* **Python** – Data analysis
* **Google Colab** – Notebook development
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualizations
* **SciPy** – Statistical hypothesis testing
* **Statsmodels** – Tukey HSD post-hoc analysis

## 🔍 Project Workflow

### 1. Data Loading and Overview

* Imported the dataset using Pandas.
* Examined the number of rows and columns.
* Checked data types and statistical summaries.
* Explored the dataset structure.

### 2. Data Cleaning and Preprocessing

* Checked for missing values and duplicate records.
* Removed duplicate records.
* Reviewed data types and data consistency.
* Created a new feature called `BMI_Category`.
* Identified BMI outliers and retained them for analysis rather than removing them automatically.

### 3. Exploratory Data Analysis (EDA)

* Performed univariate analysis to understand individual variables.
* Performed bivariate analysis to compare health factors with heart disease.
* Used groupby operations and cross-tabulations.
* Analyzed categorical and numerical variables.
* Examined correlations between numerical health variables.

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

### 5. Statistical Analysis

Applied statistical techniques to understand differences and relationships in the data.

* **Correlation Analysis:** Examined relationships between numerical health variables.
* **ANOVA Test:** Compared average BMI across different general health categories.
* **Tukey HSD Test:** Identified which general health groups had significantly different average BMI values.
* **Independent Two-Sample T-Test:** Compared average BMI between participants with and without heart disease.
* **Hypothesis Testing:** Used p-values to evaluate statistical significance.

### 6. Insights and Recommendations

* Summarized important patterns identified during the analysis.
* Compared heart disease prevalence across different health-related groups.
* Identified groups with higher observed heart disease prevalence.
* Provided practical recommendations based on the findings.

## 📊 Key Findings

* Approximately **9.04%** of the analyzed records reported heart disease.
* The **80+ age group** had the highest observed heart disease prevalence among the age groups analyzed.
* The obesity category had a higher observed heart disease prevalence (**10.62%**) than the normal BMI category (**6.92%**).
* Participants with a smoking history had a higher observed prevalence (**12.54%**) than those without a smoking history (**6.47%**).
* Participants reporting diabetes had a higher observed prevalence (**22.05%**) than those without diabetes (**6.92%**).
* Participants reporting poor general health had a higher observed prevalence (**34.11%**) than those reporting excellent general health (**2.50%**).
* Participants reporting no physical activity had a higher observed prevalence (**13.86%**) than those reporting physical activity (**7.54%**).

## 📈 Statistical Findings

### 1. ANOVA Test – BMI Across General Health Categories

* Compared average BMI across five general health categories.
* The p-value was less than 0.05.
* The result showed a statistically significant difference in average BMI among the general health groups.

### 2. Tukey HSD Test

* Performed pairwise comparisons between general health categories.
* All pairwise comparisons showed statistically significant differences.
* The largest average BMI difference was between the Excellent and Fair health groups.

### 3. Independent Two-Sample T-Test – BMI and Heart Disease

* Compared average BMI between participants with and without heart disease.
* Average BMI among participants with heart disease: **29.41**.
* Average BMI among participants without heart disease: **28.39**.
* The p-value was less than 0.05, indicating a statistically significant difference.

**Overall:** The statistical tests identified significant differences in average BMI across the analyzed groups. However, statistical significance does not establish a cause-and-effect relationship.

## 🔍 Risk-Based Insights

* Identified groups with higher observed heart disease prevalence based on health-related factors.
* Participants with a history of smoking showed higher heart disease prevalence (12.54%) than non-smokers (6.47%).
* Participants with diabetes showed higher heart disease prevalence (22.05%) than those without diabetes (6.92%).
* The obesity category showed higher heart disease prevalence (10.62%) than the normal BMI category (6.92%).
* Participants reporting poor general health showed higher prevalence (34.11%) than those reporting excellent general health (2.50%).

These findings highlight health-related risk patterns and help identify groups that may need greater health awareness and attention.

**Note:** This analysis identifies groups with higher observed heart disease prevalence based on factors such as smoking, diabetes, and BMI. These findings may help identify people who need greater health awareness and attention. However, this project does not include a machine learning prediction model or individual future risk prediction.

## 💡 Recommendations

* Encourage regular health check-ups, especially for older adults and people with existing health conditions.
* Promote physical activity and healthy lifestyle habits.
* Support smoking cessation and diabetes management.
* Encourage appropriate weight management and balanced nutrition.
* Use these findings as a starting point for further research, not as a substitute for medical advice.

## 🏁 Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize health-related data.

The analysis identified differences in observed heart disease prevalence across age groups, BMI categories, smoking status, diabetes status, general health, and physical activity.

Statistical techniques helped evaluate differences in BMI across selected groups. Overall, the findings provide useful insights into health-related patterns associated with heart disease and highlight areas for further investigation.

## 👩‍💻 Author

**Suganya**
Aspiring Data Analyst
