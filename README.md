# 🎬 Movie Performance Analysis — Patterns in Global Cinema

This project performs an in-depth exploratory data analysis (EDA) on a curated dataset of movies to uncover patterns related to **runtime, genre, revenue, director impact, and IMDb ratings**. Using Python-based data visualization and analysis, the goal is to answer: *What makes a movie successful?* and *Which factors influence a film’s critical and commercial performance?* Insights from this analysis can help filmmakers, producers, and data enthusiasts understand key success factors in global cinema.

---

## 🧪 Objectives

- Understand the **distribution of movie runtimes, IMDb ratings, and global gross earnings**.
- Identify **top-performing directors** by both quantity and average revenue.
- Explore how **genre influences movie length and box office success**.
- Analyze the **relationship between IMDb scores and revenue**.
- Visualize trends and extract actionable insights from the data.

---

## 📌 Key Methods

- **Descriptive Statistics**: Summarize central tendencies, spread, and distributions.
- **Correlation Analysis**: Examine relationships between IMDb ratings, runtime, and revenue.
- **Box Plots & Histograms**: Explore distribution and variation across genres, directors, and ratings.
- **Poisson Modeling**: Analyze director productivity and frequency of movie releases.

---

## 📷 Visualizations

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
Majority of movies range between 85 and 115 minutes.

![Distribution of Movie Runtime](images/Distribution%20of%20Movie%20Runtime.png)

---

### 🎬 Director Performance: Top 10 by Average Gross
Directors like **Christopher Nolan** and **James Cameron** lead in per-film revenue, often exceeding **500M USD**.

![Distribution of Worldwide Gross for Top 10 Directors by Average Gross](images/Distribution%20of%20Worldwide%20Gross%20for%20Top%2010%20Directors%20by%20Average%20Gross.png)

---

### 📈 Movies per Director
Most directors made 1–3 movies; very few directed more than 10.

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

## 🔍 Key Insights & Outcomes

- **Movie Length**: Most movies last between **85–115 minutes**, peaking around **100 minutes**.
- **Approval vs Success**: Films rated **6–8** are most likely to gross above **1B USD**; poorly rated ones (<4) usually underperform.
- **Director Impact**:  
   - **Steven Spielberg** and **Clint Eastwood** lead in the number of movies made.  
   - **James Cameron** and **Christopher Nolan** have the highest average gross (**400M–600M USD per movie**).
- **Genre Patterns**:
   - **Fantasy**, **Adventure**, and **Action** lead in revenue (up to **200M USD** on average).  
   - **Comedy** and **Horror** movies are shorter (~90 minutes); **Adventure** and **Fantasy** are longer (~130+ minutes).
- **IMDb Ratings**: Follow a bell-shaped curve with a peak around **6.5**.
- **Director Count Distribution**: Fits a **Poisson distribution** — most directors have small filmographies.

---

## 💻 Technologies Used

- Python 3  
- pandas  
- numpy  
- matplotlib / seaborn  
- scipy / statsmodels  
- Jupyter Notebook 

---

## 💻 Setup & Installation Instructions

Follow these steps to set up the project locally and run the analysis:

1. **Clone the Repository:**  
```bash
git clone https://github.com/indu-explores-data/Movie-Data-Analysis.git
```
2. **Navigate to the Project Directory:**
```
cd Movie-Data-Analysis
```
3. **Create and Activate a Virtual Environment (Recommended):**
```
python -m venv venv
```
**Windows:**
```
venv\Scripts\activate
```
**Mac/Linux:**
```
source venv/bin/activate
```
4. **Install Required Libraries:**
```
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```
5. **Launch Jupyter Notebook:**
```
jupyter notebook
```
6. Open Movie_Data_Analysis.ipynb and run all cells to reproduce the analysis.

---

▶️ **Usage / How to Run**

- Open Movie_Data_Analysis.ipynb in Jupyter Notebook.
- Run all cells sequentially to reproduce the visualizations and insights.
- Key insights can be found in the final sections, and visualizations are saved in the images/ folder.

---

## 🔗 **Connect with Me**

For feedback, collaboration opportunities, or related queries:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/indu-r-3a3767170/)

---

## 🙌 Feedback & Support

If you found this project helpful or interesting, feel free to ⭐ star the repository and share your thoughts. Contributions and suggestions are always welcome!
