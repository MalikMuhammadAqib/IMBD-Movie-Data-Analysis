# 🎬 IMDb Movie Data Analysis (Beginner Project)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a movie dataset sourced from IMDb.  
The dataset contains information about movies such as:

- Title  
- Genre  
- Director  
- Year  
- Runtime  
- Rating  
- Votes  
- Revenue (Millions)  

The goal of this project is to clean the data, analyze trends, and extract meaningful business insights from movie performance metrics.

---

## 🎯 Business Problem Statement

The entertainment industry relies heavily on ratings, audience engagement, and revenue performance to make strategic decisions.

This project aims to answer the following business questions:

1. Which years had the highest average votes and revenue?
2. Does a higher movie rating lead to higher revenue?
3. Which directors consistently produce highly rated movies?
4. What are the top 10 highest-rated and highest-revenue movies?
5. Which genres dominate movie production?
6. How are movies distributed across years?
7. How can movies be categorized based on rating performance?

By answering these questions, we can better understand what drives financial success in the movie industry.

---

## 🧹 Data Cleaning & Preparation

The following steps were performed:

- Checked dataset shape and structure
- Inspected data types
- Identified and visualized missing values
- Removed rows with missing values
- Checked for duplicate records
- Generated descriptive statistics

---

## 📊 Exploratory Data Analysis

### 1️⃣ Long Duration Movies
- Identified movies with runtime ≥ 180 minutes.

### 2️⃣ Year with Highest Average Votes
- Grouped data by year to analyze audience engagement trends.

### 3️⃣ Year with Highest Average Revenue
- Calculated average revenue per year to detect strong financial periods.

### 4️⃣ Director Performance Analysis
- Calculated average rating per director.
- Identified directors producing consistently high-rated movies.

### 5️⃣ Top 10 Longest Movies
- Extracted using `nlargest()` function.

### 6️⃣ Number of Movies Per Year
- Analyzed yearly production trends.

### 7️⃣ Most Popular Movie (Highest Revenue)
- Identified the movie with maximum revenue.

### 8️⃣ Top 10 Highest Rated Movies
- Ranked movies based on rating.

### 9️⃣ Top 10 Highest Revenue Movies
- Ranked movies based on revenue.

### 🔟 Rating vs Revenue Analysis
- Created scatter plot between rating and revenue.
- Observed a positive correlation trend.

### 1️⃣1️⃣ Movie Classification Based on Rating
Movies were categorized as:
- ⭐ Excellent (Rating ≥ 7.5)
- 👍 Good (Rating ≥ 6.0)
- 📉 Average (Below 6.0)

### 1️⃣2️⃣ Genre Analysis
- Counted total movies per genre.
- Identified dominant genres.
- Extracted unique genres.

---

## 📈 Key Insights

- Higher-rated movies tend to generate higher revenue, although rating alone does not guarantee financial success.
- Some directors consistently produce highly rated films.
- Certain genres dominate production volume.
- Movie production and revenue fluctuate by year.
- Longer runtime does not necessarily mean higher profitability.

---

## 🛠️ Tools & Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 Skills Demonstrated

- Data Cleaning  
- Handling Missing Data  
- Data Aggregation (GroupBy)  
- Data Visualization  
- Feature Engineering  
- Business Insight Extraction  
- Exploratory Data Analysis  

---

## 📌 Conclusion

This beginner-level project demonstrates the ability to transform raw movie data into actionable business insights.  

The analysis highlights the relationship between ratings and revenue, identifies key performance drivers such as directors and genres, and showcases how data-driven decisions can support strategic planning in the entertainment industry.

---
