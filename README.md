# 🍿 Netflix Data Cleaning and Exploratory Data Analysis (EDA)

This project focuses on analyzing the Netflix dataset using Python. It is divided into two major parts: **Data Cleaning** and **Exploratory Data Analysis**. The goal is to understand content trends, uncover patterns in movie/show additions, and identify popular genres, countries, and more.

---

## 📁 Project Structure


---

## 📌 Objective

- Clean raw Netflix dataset to make it analysis-ready
- Perform EDA to identify trends in content type, genre, release year, country, etc.
- Visualize the results using Python libraries

---

## 📦 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Part 1: Data Cleaning

Performed in `Netflix_Data_Cleaning.ipynb`, including:

- Dropping duplicates
- Handling missing values
- Converting date columns to datetime format
- Splitting multi-value columns (like cast, director)
- Fixing data types (e.g., duration column)

---

## 📊 Part 2: Exploratory Data Analysis

Performed in `Netflix_EDA_Analysis.ipynb`, including visual answers to:

- 📆 **What is the trend of Netflix content addition over years?**
- 🎬 **What is the ratio of Movies vs TV Shows?**
- 🌍 **Which countries produce the most Netflix content?**
- 👩‍🎤 **Top actors and directors in Netflix content**
- 🕐 **Distribution of content by duration**
- 🏷 **Most common genres and categories**

---

## 🔍 Key Insights

- **Movies** dominate Netflix's content, with ~70% share.
- Netflix content addition peaked in **2019 and 2020**.
- **USA** leads in content production, followed by India and the UK.
- **Drama** is the most common genre.
- A few directors and actors have contributed heavily to the platform.
- Most TV Shows have **shorter episode durations**, while movies vary widely.

---

## 📸 Sample Visuals

_Add images from your EDA notebook here by exporting graphs and saving in an `/images/` folder._

```markdown


---

## 🛠 Next Steps

1. Rename the notebooks:
   - `Netflix_Data_Cleaning.ipynb`
   - `Netflix_EDA_Analysis.ipynb`

2. Create `images/` folder (optional):
   - Export graphs as PNGs and put them inside `images/`
   - Link them in your README like this:

     ```markdown
     ![Sample Chart](images/plot_name.png)
     ```

3. Copy the entire `README.md` text above and paste it into your GitHub repo.

---

If you want, I can also:
- Generate this README as a downloadable `.md` file
- Extract images for you (once the file issue is resolved)
- Review your EDA and list **custom insights from your notebook**

Let me know! ​:contentReference[oaicite:0]{index=0}​

![Content Trend](images/content_added_by_year.png)
![Top Countries](images/top_countries.png)
