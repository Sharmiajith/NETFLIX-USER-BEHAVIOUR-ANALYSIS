📊 Netflix User Behavior Analysis
📌 Project Overview
This project focuses on analyzing Netflix user behavior using exploratory data analysis (EDA) techniques. The goal is to understand user patterns related to demographics, subscription types, device usage, activity status, revenue, and churn behavior through data visualization and statistical insights.
The analysis helps identify trends that can support business decisions, customer retention strategies, and revenue optimization.
🛠️ Technologies Used
Python
NumPy – numerical computations
Pandas – data manipulation and analysis
Matplotlib – data visualization
Seaborn – advanced and aesthetic visualizations
📚 Libraries Imported
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set(color_codes=True)
%matplotlib inline
import warnings
warnings.filterwarnings("ignore")
📂 Dataset Description
The dataset contains information related to Netflix users, including:
Gender
Age
Country
Subscription Type
Monthly Revenue
Device Type
User Activity Status (Active/Inactive)
Churn Information
🔍 Exploratory Data Analysis (EDA)
The following analyses and visualizations are performed:
Gender distribution of users
Age distribution and age group analysis
Country-wise user distribution
Subscription type distribution
Active vs inactive users by subscription
Average monthly revenue by subscription type
Churn rate analysis
Device usage distribution
Correlation matrix to identify feature relationships
📈 Key Insights
User demographics show variations across gender and age groups
Subscription type impacts revenue and churn rate
Certain devices are more popular among active users
Higher churn is observed in specific subscription plans
(Insights may vary based on dataset version)
🎯 Project Objectives
Understand customer behavior patterns
Identify factors influencing churn
Analyze revenue trends by subscription
Support data-driven business strategies
🚀 Future Enhancements
Build a machine learning churn prediction model
Create an interactive dashboard (Power BI / Streamlit)
Perform customer segmentation using clustering
Add time-based trend analysis
📌 Conclusion
This Netflix behavior analysis provides valuable insights into user engagement, subscription trends, and churn patterns. The findings can help streaming platforms improve customer retention and optimize pricing strategies.
