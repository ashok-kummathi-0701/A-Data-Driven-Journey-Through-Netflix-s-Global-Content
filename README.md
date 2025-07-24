
# 📊 Netflix Titles EDA Report

This repository contains an exploratory data analysis (EDA) of the [Netflix Titles dataset](https://www.kaggle.com/shivamb/netflix-shows), which includes information about movies and TV shows available on Netflix as of 2021.

---

## 📁 Dataset Overview

- **Total Records**: 8807
- **Columns**: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🧪 EDA Objectives

- Understand the distribution of Movies vs TV Shows
- Identify top genres, countries, and directors
- Explore time-based trends like content release and addition patterns
- Analyze durations and common cast members

---

## 🔍 Key Findings

### 1. 📺 **Content Type Distribution**
- Movies dominate the platform, making up around 70% of the content.
- TV Shows make up the remaining 30%.

### 2. 🌍 **Top 10 Countries by Content Count**
| Country | Count |
|---------|-------|
| United States | Most entries |
| India | Second highest |
| Others include UK, Canada, Japan, etc. |

### 3. 🎭 **Most Common Genres**
- International Movies
- Dramas
- Comedies
- Action & Adventure
> Many shows fall under multiple genres.

### 4. 🎬 **Top Directors**
- Rajiv Chilaka
- Jan Suter
- Jay Karas
- More prominent names appear frequently.

### 5. 🧑‍🤝‍🧑 **Top Cast Members**
- Anupam Kher, Rupa Bhimani, and others appear in multiple titles.

### 6. ⏰ **Content Added Over Time**
- Rapid growth in content additions from 2016–2020.
- Monthly additions show seasonal and yearly trends.

### 7. 🕒 **Duration Analysis**
- Movies mostly range from 60–120 minutes.
- TV Shows mostly run for 1–2 seasons.

---

## 📈 Visualizations

All charts are saved as PNGs:
- <img width="640" height="480" alt="Content_type_distributio" src="https://github.com/user-attachments/assets/866683ab-e89b-4c4b-af20-93f6c33404dc" />
- <img width="640" height="480" alt="top_10_Countries_with_Most_Netflix_Titles" src="https://github.com/user-attachments/assets/6a3e25d4-891d-4508-915d-d785208c3f60" />


- `content_type_distribution.png`
- `top_10_countries.png`
- `top_10_genres.png`
- `top_10_directors.png`
- `top_10_actors.png`
- `release_trend.png`
- `monthly_additions.png`
- `duration_distribution.png`
- `tv_vs_movies_trend.png`
- `missing_values_heatmap.png`

---

## 📂 How to Run This Project

1. Clone the repo and install requirements:
```bash
pip install pandas matplotlib seaborn
```

2. Run the analysis script:
```bash
python netflix_eda_report.py
```

3. Explore the generated plots in your local folder.

---

## 📌 Credits

- Dataset: [Netflix Titles on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- Analysis: Created using Python, Pandas, Seaborn, and Matplotlib.

---

