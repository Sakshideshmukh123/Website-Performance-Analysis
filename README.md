# 🌐 Website Performance Analysis

## 📌 Project Overview

This project focuses on analyzing website performance metrics using real-world web analytics data. The dataset was initially in raw format and required data cleaning, transformation, and exploratory analysis to extract meaningful business insights.

The objective of this project is to understand traffic trends, evaluate marketing channel effectiveness, analyze engagement behavior, and identify peak performance hours.

---

## 🎯 Business Objectives

This project answers the following analytical questions:

- What trends are observed in users and sessions over time?
- Which marketing channel generates the highest users?
- Which channel has the highest average engagement time?
- How does engagement rate vary across channels?
- Which channels drive more engaged sessions?
- At what hours does each channel generate peak traffic?
- Is there a relationship between sessions and engagement rate?

---

## 📊 Dataset Description

The dataset contains 3,180 records of hourly website performance data with the following features:

- Channel group (traffic source)
- DateTime (YYYYMMDDHH format)
- Users
- Sessions
- Engaged Sessions
- Average engagement time per session
- Engagement rate
- Event count
- Events per session

The data covered website activity from April 6, 2024 to May 3, 2024.

---

## 🧹 Data Cleaning & Preprocessing

The dataset was not analysis-ready and required the following steps:

- Assigned first row as proper column headers
- Removed redundant header row
- Converted all numeric columns from object to numeric data types
- Converted DateTime column into datetime format
- Extracted hour feature for time-based analysis
- Handled missing or invalid values using safe conversion methods

This preprocessing ensured accurate analysis and visualization.

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Time-series analysis of Users and Sessions
- Channel-wise total users comparison
- Average engagement time by channel
- Engagement rate comparison across channels
- Engaged vs Non-engaged sessions analysis
- Heatmap visualization of hourly traffic by channel
- Correlation analysis between Sessions and Engagement Rate

---

## 📈 Key Insights

- A clear daily cyclical traffic pattern was observed.
- Sessions consistently exceeded users, indicating repeat visits.
- Organic Video channel showed the highest average engagement time.
- Referral traffic demonstrated strong engagement performance.
- Peak website activity occurred during daytime hours.
- Engagement rate varied across channels, indicating differences in traffic quality.
- Certain traffic spikes suggest possible campaign-driven activity.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run This Project

1. Clone the repository
2. Install required libraries:

```
pip install -r requirements.txt
```

1. Open the notebook file
2. Run all cells sequentially

---

## 📁 Project Structure

```
Website-Performance-Analysis/
│
├── Website_Performance_Analysis.ipynb
├── website_data.csv
├── README.md
```
