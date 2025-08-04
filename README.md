# 🎬 Movie Data Analysis - Uncovering Patterns in Global Cinema

This project performs an in-depth exploratory data analysis (EDA) on a curated dataset of movies to derive insights into trends related to runtime, genre, revenue, director impact, and IMDb ratings. Using Python-based data visualization and analysis, the goal is to answer: *What makes a movie successful?* and *Which factors influence a film’s critical and commercial performance?*

---

## 📌 Project Objectives

- Understand the **distribution of movie runtimes**, ratings, and gross earnings.
- Identify **top-performing directors** by both quantity and profitability.
- Explore how **genre influences movie length and box office success**.
- Analyze the **relationship between IMDb scores and revenue**.
- Visualize trends and extract actionable insights from the data.

---


## 📊 Visual Insights

### 🎯 Approval Index vs Worldwide Gross
Shows a strong positive correlation between IMDb ratings (approval) and global revenue.

![Approval Index vs Worldwide Gross](images/Approval%20Index%20vs%20Worldwide%20Gross.png)

---

### ⏱️ Runtime by Genre
Highlights how different genres vary in movie duration.

![Box Plot of Runtime by Genre](images/Box%20Plot%20of%20Runtime%20by%20Genre.png)

---

### ⭐ IMDb Rating Distribution
IMDb ratings mostly fall between 5.5–7.5, with a central tendency near 6.5.

![Distribution of IMDb Ratings](images/Distribution%20of%20IMDb%20Ratings.png)

---

### ⌛ Runtime Distribution
Majority of films range between 85 and 115 minutes.

![Distribution of Movie Runtime](images/Distribution%20of%20Movie%20Runtime.png)

---

### 🎬 Director Performance: Top 10 by Average Gross
Directors like **Christopher Nolan** and **James Cameron** lead in per-film revenue, often exceeding **500M USD**.

![Distribution of Worldwide Gross for Top 10 Directors](images/Distribution%20of%20Worldwide%20Gross%20for%20Top%2010%20Directors%20by%20Average%20Gross.png)


---

### 📈 Movies per Director

Most directors made 1–3 films; very few directed more than 10.
![Histogram of Movies per Director](images/Histogram%20of%20Movies%20per%20Director.png)

---

### 🎭 Most Common Genres

Drama, Comedy, Action, and Thriller dominate genre frequency.
![Top 10 Most Common Genres](images/Top%2010%20Most%20Common%20Genres.png)

---

### 🌍 Global Gross by Genre

Fantasy, Action, and Adventure genres bring in the highest average global earnings.
![Worldwide Gross by Main Genre](images/Worldwide%20Gross%20by%20Main%20Genre.png)

---

## 🔍 Key Insights

- **Movie Length**: Most movies last between **85–115 minutes**, with a peak at **~100 minutes**.
- **Approval vs Success**: Films rated **6–8** are most likely to gross above **$1B USD**; poorly rated ones (<4) usually underperform.
- **Director Impact**:  
   - **Steven Spielberg** and **Clint Eastwood** lead in number of films made.
   - **James Cameron** and **Christopher Nolan** have the highest average gross, between **$400M–600M USD per film**.
- **Genre Patterns**:
   - **Fantasy**, **Adventure**, and **Action** lead in revenue (up to **$200M USD** on average).
   - **Comedy** and **Horror** films are shorter (~90 minutes); **Adventure** and **Fantasy** are longer (~130+ minutes).
- **IMDb Ratings**: Follow a bell-shaped curve with a peak around **6.5**.
- **Director Count Distribution**: Fits a **Poisson distribution** - most directors have small filmographies.

---

## 🧰 Tools & Technologies

| Tool/Library        | Purpose                                                       |
| ------------------- | ------------------------------------------------------------- |
| **Python**          | Core scripting and data analysis                              |
| **Pandas**          | Data cleaning, transformation, and wrangling                  |
| **NumPy**           | Numerical operations and array handling                       |
| **Matplotlib**      | Basic data visualization                                      |
| **Seaborn**         | Statistical plotting and aesthetic visualizations             |
| **SciPy (Poisson)** | Statistical modeling (used to model director productivity)    |
| **Jupyter Lab**     | Interactive notebook interface for analysis and visualization |


---

## 📬 Let's Connect

- **LinkedIn:** [Indu R](https://www.linkedin.com/in/indu-r-3a3767170/)

- ---

## 🙌 Feedback & Support

If you found this project helpful or interesting, feel free to ⭐ star the repository and share your thoughts. Contributions and suggestions are always welcome!




