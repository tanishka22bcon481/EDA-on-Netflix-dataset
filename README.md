# EDA-on-Netflix-dataset
A data science project performing exploratory data analysis (EDA) on Netflix's movies and TV shows dataset using Python. The project explores trends in content type, genres, release years, country-wise distribution, and content ratings with visualizations. Built using pandas, seaborn, and matplotlib in a Jupyter Notebook environment.

---

## 📁 Dataset

- Source: [Netflix Movies and TV Shows Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- File: `netflix_titles.csv`
- Size: ~6,000+ titles with features like `title`, `type`, `release_year`, `country`, `rating`, `genres`, etc.

---

## 🧠 Objective

The goal is to answer questions such as:

- What is the ratio of Movies vs TV Shows on Netflix?
- What are the top genres available?
- Which years had the most content releases?
- Which countries contribute the most content?
- What kind of content is associated with which rating?

---

## 🛠 Tools Used

- **Python**  
- **Libraries:** `pandas`, `matplotlib`, `seaborn`, `wordcloud` (optional)
- **Platform:** Jupyter Notebook

---

## 📌 Key Steps in the Project

1. **Data Loading**  
   Load `netflix_titles.csv` using pandas.

2. **Data Cleaning**  
   - Handle missing values
   - Convert date columns
   - Create new features (`year_added`)

3. **Exploratory Data Analysis (EDA)**  
   - Movie vs TV Show distribution
   - Top genres
   - Year-wise release trend
   - Country-wise content count
   - Ratings distribution
   - Heatmap of Ratings vs Type

4. **Visualizations**  
   Created using `matplotlib` and `seaborn`, including:
   - Bar charts
   - Line plots
   - Heatmaps
   - Word clouds (optional)

---

## 📈 Sample Visuals

- 🎞️ Movies vs TV Shows  
- 🌍 Top 10 Countries by Content  
- 🎭 Top 10 Genres  
- 🧯 Ratings vs Type Heatmap  
- 📆 Content Release Over Years

---

## 🔍 Key Insights

- **Movies** outnumber TV Shows on Netflix.
- **Drama**, **Comedies**, and **International content** are the most frequent genres.
- Content release increased sharply after **2015**, peaking around **2019–2020**.
- The **United States** contributes the most content.
- Most content is rated **TV-MA**, especially for Movies.
