Student Performance and Academic Risk Analytics
📊 Exploratory Data Analysis of Multi-Source Educational Data Using Python
Project Overview

This project analyses student academic performance and academic risk using a multi-source educational dataset containing demographic, academic, behavioural and contextual information. The project applies an end-to-end Exploratory Data Analysis (EDA) workflow using Python to identify patterns and relationships associated with student outcomes.

The analysis particularly focuses on the relationship between Virtual Learning Environment (VLE) engagement, academic performance and academic risk, while also examining demographic, educational, regional and socioeconomic factors.

🎯 Aim

To conduct a comprehensive exploratory data analysis of multi-source educational data to identify demographic, behavioural, academic and contextual factors associated with student academic performance and academic risk using Python.

📌 Objectives
Import and explore the educational dataset using Python.
Clean and preprocess the dataset.
Examine missing values, duplicates, data types and categorical variables.
Conduct univariate, bivariate and multivariate EDA.
Analyse relationships between student engagement and academic outcomes.
Examine demographic, educational, regional and contextual patterns.
Perform correlation, GroupBy and pivot-table analysis.
Create meaningful data visualisations using Python.
Generate actionable, data-informed insights and recommendations.
📂 Dataset

The project uses:

Multi-Source Educational Analytics Dataset for Student Performance and Contextual Analysis

Authors: Elzeki, O., Kamel, G., Sameh, S., Amria, O., Moharam, O., & Ismail, A.
Year: 2026
Version: 1
Source: Mendeley Data
DOI: 10.17632/rkrptyy994.1

The dataset contains:

32,593 records
20+ variables
Demographic information
Academic information
VLE engagement measures
Regional socioeconomic indicators
Academic outcome/risk information
Main Variables
Category	Examples
Student demographics	Gender, age band, region
Educational background	Highest education, previous attempts
Academic information	Studied credits, final weighted score
VLE engagement	Total clicks, materials accessed, assessments submitted
Contextual factors	Unemployment rate, broadband speed
Outcome	Academic risk
🛠️ Technologies Used
Python
Jupyter Notebook
Pandas – Data manipulation and analysis
NumPy – Numerical operations
Matplotlib – Data visualisation
Seaborn – Statistical visualisation
Plotly – Interactive visualisation
🔄 Project Workflow
Dataset
   ↓
Data Loading
   ↓
Initial Data Exploration
   ↓
Data Cleaning & Pre-processing
   ↓
Feature Preparation
   ↓
Univariate Analysis
   ↓
Bivariate Analysis
   ↓
Multivariate Analysis
   ↓
Correlation & GroupBy Analysis
   ↓
Pivot Table Analysis
   ↓
Data Visualisation
   ↓
Key Insights
   ↓
Recommendations
   ↓
Conclusion
🧹 Data Cleaning and Pre-processing

The following preprocessing activities were performed:

Checked dataset dimensions and structure.
Examined variable data types.
Checked for missing values.
Checked for duplicate records.
Examined categorical variables and their frequencies.
Reviewed numerical variables using descriptive statistics.
Investigated unusual values and distributions.
Prepared engagement-related variables for analysis.
Used filtering and aggregation where appropriate.
Prepared grouped datasets for regional, module, engagement and risk analysis.
📈 Exploratory Data Analysis

The analysis included:

Univariate Analysis

Examined individual variables such as:

Gender
Age band
Academic risk
Final weighted score
VLE clicks
Engagement level
Bivariate Analysis

Examined relationships between:

Engagement and academic score
Engagement and academic risk
Previous attempts and academic performance
Education level and academic risk
Region and academic performance
VLE clicks and academic scores
Learning-material access and academic performance
Multivariate Analysis

The project also used:

Correlation analysis
Correlation heatmaps
Pivot tables
Engagement-level comparisons
Course-module comparisons
Group-based analysis
📊 Visualisations

The project includes 15 visualisations, exceeding the minimum requirement of 10.

Visualisation techniques include:

Bar charts
Pie charts
Histograms
Box plots
Scatter plots
Correlation heatmaps
Pivot heatmaps
Distribution plots
Comparative visualisations

The visualisations were used to identify patterns in student engagement, academic performance, academic risk and contextual variables.

🔍 Key Findings

The analysis identified several important patterns:

Higher VLE engagement is associated with higher academic scores.
Low-engagement students show considerably higher levels of academic risk.
Total VLE clicks, learning-material access and assessment submission are positively associated with academic performance.
Students with lower prior educational attainment generally show higher academic risk.
Regional differences exist in average academic performance.
Students with multiple previous course attempts show differences in academic performance.
VLE engagement variables show stronger relationships with academic performance than the examined contextual variables.
Average regional broadband speed shows a relatively weak relationship with individual academic outcomes.
💡 Recommendations

Based on the EDA findings, the following recommendations are proposed:

Target low-engagement students: Monitor low VLE clicks, limited material access and low assessment submission to identify students requiring additional support.
Introduce early engagement monitoring: Track VLE activity during the early stages of courses to identify disengagement and provide timely academic guidance.
Encourage learning-material use: Encourage students to access a wider range of relevant learning resources.
Improve assessment participation: Use reminders, clearer communication and academic support to encourage timely assessment submission.
Support students with lower educational attainment: Provide foundation resources, academic-skills workshops and additional tutoring.
Support repeat-attempt students: Offer personalised guidance and progress monitoring to students with multiple previous attempts.
Monitor engagement by module: Analyse module-level engagement and investigate areas where low engagement coincides with poorer outcomes.
Prioritise student-level support: Greater attention should be given to student engagement and academic support rather than relying primarily on regional broadband indicators.

Author
JISHA P K
🎓 Academic Project
Project Domain: Education Analytics
Project Type: Exploratory Data Analysis
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly
Analysis Environment: Jupyter Notebook
