# 🎬 Netflix Data Cleaning & Exploratory Data Analysis (EDA)

This project demonstrates my end-to-end data analysis skills using the Netflix dataset. It is structured into two key phases — **Data Cleaning** and **Exploratory Data Analysis** — to prepare, analyze, and derive insights from real-world data.

---

## 🚀 Project Overview

Netflix, one of the leading streaming platforms globally, hosts thousands of titles including movies and TV shows. This project explores the Netflix catalogue to uncover patterns in content distribution, genre trends, and temporal behavior of title additions.

The project covers:

- Cleaning raw Netflix data to make it analysis-ready
- Identifying trends in content type, release dates, genres, and more
- Visualizing insights through compelling charts

---

## 🧠 Key Business Questions

- How has Netflix's content grown over the years?
- What is the distribution between Movies and TV Shows?
- Which countries produce the most Netflix content?
- What genres dominate the platform?
- Who are the most frequent actors and directors?

---

## 📊 Summary of Insights

✔️ **Movies** constitute over 70% of the platform’s content  
✔️ Most content was added in **2019–2020**, indicating rapid expansion  
✔️ **USA** dominates in content production, followed by **India**  
✔️ **Drama** and **Comedies** are the most popular genres  
✔️ Netflix favors **short-duration content** for TV Shows  
✔️ A few directors and actors repeatedly appear across titles

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** & **Seaborn** – data visualization
- **Jupyter Notebook** – interactive development

---

## 🧹 Phase 1: Data Cleaning (`Netflix_Data_Cleaning.ipynb`)

> 📌 Objective: Clean and prepare the dataset for analysis

**Steps Performed:**
- Removed duplicates and missing values
- Converted date columns to datetime format
- Standardized column formats and string values
- Separated combined columns (e.g., multiple genres or cast members)
- Cleaned `duration`, `rating`, and categorical columns

---

## 📈 Phase 2: Exploratory Data Analysis (`Netflix_EDA_Analysis.ipynb`)

> 📌 Objective: Analyze content trends and answer key questions

**Key Analyses Included:**
- Year-wise content addition trend
- Distribution of content type (Movie vs TV Show)
- Top 10 countries with the most content
- Most frequent genres using exploded columns
- Top 10 directors and actors with the highest appearances
- Duration comparison between Movies and TV Shows
- Heatmaps and bar charts for visual storytelling

---

## 📂 Dataset Information

- **Source**: [Kaggle – Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Rows**: ~6,000+ entries
- **Columns**: Show ID, Title, Type, Country, Date Added, Release Year, Duration, Genre, Cast, Director, etc.

---

## 📸 Sample Visualizations

_(Add image files in `/images/` folder and link them here)_

```markdown
![Content Over Time](images/content_over_years.png)
![Top Genres](images/top_genres.png)
![Movie vs TV](images/type_distribution.png)
