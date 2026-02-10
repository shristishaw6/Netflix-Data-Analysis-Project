# 🎬 Netflix Data Analysis Project

## 📌 Overview
This project performs an in-depth exploratory data analysis (EDA) on Netflix's Movies and TV Shows dataset. The goal is to understand content trends, distribution patterns, and key insights related to genres, ratings, countries, directors, and release timelines.

The analysis is done using Python with a strong focus on data cleaning, transformation, and visualization.

---

## 📂 Dataset
- Source: Netflix Movies and TV Shows dataset (CSV)
- Total records after cleaning: ~198K
- Content Types: Movies & TV Shows

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (for interactive visuals)

---

## 🧹 Data Cleaning & Preparation
- Removed duplicate records
- Handled missing values in columns like director, cast, country, rating
- Converted `date_added` to datetime format
- Extracted new features:
  - Day, Month, Year
  - Month Name
  - Weekday
- Standardized rating categories into:
  - Kids
  - Teens
  - Adults
- Split and normalized multi-value columns:
  - Genre
  - Cast
  - Director
  - Country

---

## 📊 Exploratory Data Analysis (EDA)
Key analyses performed:
- Distribution of Movies vs TV Shows
- Top content-producing countries
- Top directors (Movies & TV Shows)
- Most popular genres
- Content classification by age rating
- Year-wise, month-wise, and day-wise content additions
- Duration analysis for Movies
- Season count analysis for TV Shows

---

## 📈 Visualizations
- Pie charts for content distribution
- Bar charts for top countries, genres, and directors
- Stacked bar charts for country-wise content comparison
- Time-based trend analysis (Year / Month / Weekday)
- Histograms for duration and seasons

---

## 🔍 Key Insights
- Movies dominate Netflix’s content library compared to TV Shows
- The United States and India contribute the highest number of titles
- Drama and International content are among the most popular genres
- Majority of content is targeted toward Adults
- Significant growth in content additions after 2016

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
2. Install required libraries

   pip install pandas numpy matplotlib seaborn plotly
3. Run the Jupyter Notebook

   jupyter notebook
