# Student-Performance-Heart-Disease-Data-Visualization
A data visualization project that analyzes student academic performance and heart disease risk factors using statistical plots, distributions, correlations, and comparative charts to uncover meaningful insights.


📌 Project Description

This project focuses on exploratory data analysis and statistical visualization using two real-world datasets:

Student Performance Dataset – GPA, study time, absences, and grade class

Heart Attack South Africa Dataset – medical risk factors and heart attack outcomes

The goal is to transform raw data into clear, meaningful visual insights using professional plotting techniques. The notebook demonstrates data cleaning, aggregation, distribution analysis, correlation analysis, and categorical comparisons through multiple visualization types.


🎯 Objectives

The project aims to:

Clean and prepare datasets

Analyze academic performance trends

Explore relationships between study habits and GPA

Investigate heart disease risk factors

Visualize distributions and correlations

Improve interpretation using well-styled charts

🛠 Technologies Used

Python

Pandas – data manipulation

Matplotlib – base plotting

Seaborn – advanced statistical visualizations

Google Colab – notebook execution environment


📂 Project Structure
week5-visualization-project/
│
├── data/
│   ├── student_data.csv
│   └── heart_attack_south_africa.csv
│
├── notebook/
│   └──students/Hdra_data analysis_visualizations.ipynb
│
├── outputs/
│   └── figures/
│
└── README.md

📊 Visualizations Implemented
🔵 work 2 – Student Dataset
1. Bar Chart – Average GPA by Grade Class

Grouped GPA by grade class

Mean GPA calculated

Gradient colormap applied

Bar annotations added

Highlights which classes perform best academically

2. Scatter Matrix – Study Habits vs GPA

Variables: StudyTimeWeekly, Absences, GPA

Diagonal histograms show distributions

Scatter plots reveal correlations

Helps identify how habits affect performance

3. Box Plot – Study Time Distribution by Grade

Shows median, quartiles, and outliers

Compares study effort between grade levels

Highlights variability in study behavior

🔴 work 3 – Heart Disease Dataset
4. KDE Plot – Age vs Heart Attack Outcome

Density curves by outcome group

Smoothed distribution

Median line added

Shows which age groups are most at risk

5. Correlation Heatmap

Displays correlation matrix of numeric features

Half-masked for readability

Identifies strongest risk factor relationships

6. Boxplot – Cholesterol by Outcome & Gender

Gender comparison using hue

Outliers reduced for clarity

Shows cholesterol differences across groups

7. Pairplot – Multiple Risk Factors

Pairwise relationships among key variables

KDE on diagonals

Useful for spotting trends and separability

8. Violin Plot – Blood Pressure Distribution

Displays full distribution shape

Compares systolic vs diastolic

Split view improves clarity

9. Countplot – Smoking vs Heart Attack

Counts smokers vs non-smokers

Grouped by gender

Shows behavioral risk patterns
