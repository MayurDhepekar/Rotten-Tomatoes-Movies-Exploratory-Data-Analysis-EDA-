# 🎬 Rotten Tomatoes Movies – Exploratory Data Analysis (EDA)

This project explores movie rating data from **Rotten Tomatoes** with a focus on comparing **critic (Tomatometer)** and **audience ratings** for popular films. The dataset comes from **Maven Analytics**, and the analysis highlights trends across genres, runtime, release year, and viewer count.

---

## 📌 Project Objective

To identify patterns in how movies are rated by critics versus general audiences, especially in movies released after 2010. The project uses Python libraries to clean the data, engineer new features, and visualize key insights.

---

## 🧾 Dataset Overview

- **Source:** Maven Analytics – Rotten Tomatoes Movies Dataset  
- **Initial Shape:** 16,638 rows × 9 columns  
- **Filtered Dataset (`movies_popular`):** 316 movies with audience count > 100,000  
- **Key Columns Used:**
  - `movie_title`
  - `rating`
  - `genre`
  - `in_theaters_date`
  - `runtime_in_minutes`
  - `tomatometer_rating`
  - `tomatometer_count`
  - `audience_rating`
  - `audience_count`

---

## 🧰 Tools & Technologies

- Python 3  
- Pandas – data manipulation  
- NumPy – conditional feature creation  
- Matplotlib & Seaborn – data visualization  
- Jupyter Notebook – for interactive development  

---

## 🧹 Step A: Data Cleaning & Preparation

- Removed irrelevant columns  
- Converted `in_theaters_date` to datetime format  
- Filtered to include movies released in or after 2010  
- Created a refined dataset `movies_popular` (audience_count > 100K)  

---

## 🛠 Step B: Feature Engineering

- Extracted a `year` column from the release date  
- Created binary columns for genres:
  - `Animation`
  - `Action & Adventure`
  - `Comedy`

---

## 📈 Step C: Exploratory Data Analysis (EDA)

### General Observations:
- Most frequent ratings: **PG-13**, **R**, and **PG**
- PG-13 movies have the **highest average audience rating**
- Animated movies receive **consistently higher ratings**
- Comedy tends to have **lower average scores**
- **Shutter Island** has the highest audience count (2M+)

---

## 📊 Visualizations Created

- ✅ Top 10 longest movies  
- ✅ Critic rating vs runtime (scatter plot)  
- ✅ Highest-rated movies (audience & critics)  
- ✅ Correlation heatmap of numeric variables  
- ✅ Pairplot of ratings and counts  
- ✅ Bar chart of most frequent genres  
- ✅ Stacked bar plot of ratings by genre  
- ✅ Violin plots, boxplots, and count plots

---

## 🔍 Key Insights

- **Audience ratings** are generally higher than **critic ratings**  
- **Animated movies** perform best across both rating types  
- **Comedy and Drama** are the most common genres  
- **No strong correlation** between runtime and ratings  
- Surge in movie popularity and ratings after **2010**  
- **Shutter Island** may be an outlier due to its high audience count

---


## 🙌 Acknowledgments

- **Dataset**: [Maven Analytics Data Playground](https://www.mavenanalytics.io/data-playground)
- **Instructor**: Alice Zhao (Project Guidance)

---

## 📬 Let's Connect!

If you're working on similar projects or learning data analytics, feel free to connect with me!

📧 mayurdhepekar@email.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mayurdhepekar/))  
