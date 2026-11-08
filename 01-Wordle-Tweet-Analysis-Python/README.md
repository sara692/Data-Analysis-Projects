# 🟩 Wordle Tweets Analysis

This project explores how players around the world solved **Wordle** puzzles, based on thousands of tweets shared publicly.  
The aim is to study **performance trends, solving efficiency, and puzzle difficulty** using Python and data analysis techniques.

---

## 📂 Dataset
- Source: Kaggle Wordle tweets dataset  
- Structure: Each row represents a tweet containing:
  - `tweet_date`: When the tweet was posted  
  - `wordle_id`: Puzzle number (e.g., Wordle 210)  
  - `n_attempts`: Number of guesses used  
  - `tweet_text`: Game grid (🟩 🟨 ⬛) showing guesses and outcomes  

---

## 🔍 Key Analyses

### 1. Tweet Activity
- **Question:** What days of the week see the most Wordle tweets?  
- **Method:** Convert datetime to day names, count frequency, and plot.  
- **Insight:** Peaks show when the community is most engaged.  

### 2. Performance by Puzzle
- **Question:** Does performance (attempts to solve) change over different Wordle IDs?  
- **Method:** Group by `wordle_id` and `n_attempts`.  
- **Visuals:** Heatmaps & bar charts showing attempts distribution.  

### 3. Correctness Percentage
- **Question:** What percentage of guesses are correct (green tiles)?  
- **Method:** Extract 🟩, 🟨, ⬛ from tweet text.  
  - Calculate `% greens = greens / total_boxes * 100`  
- **Visuals:**  
  - Histogram of green percentages across all games  
  - Top 10 easiest & hardest Wordles by average green %  
- **Insight:** Some puzzles clearly stand out as more/less solvable.  

### 4. Efficiency of Solving
- **Question:** How quickly do players improve across attempts?  
- **Method:** Track greens gained per attempt (attempt 1 → attempt 2 → …).  
- **Visuals:** Line plots showing average greens per attempt number.  
- **Insight:** Players usually gain the most greens in early attempts, with diminishing returns later.  

---

## 📊 Tools & Techniques
- **Pandas**: cleaning, grouping, feature extraction  
- **Regex & string methods**: extracting emoji-based features from tweets  
- **Matplotlib / Seaborn**: data visualization and storytelling  
- **Jupyter Notebook**: iterative exploration and reporting  

---

## 🚀 Future Work
- Sentiment analysis of tweet text (beyond the grid)  
- Compare performance by player type (casual vs. frequent posters)  
- Predict puzzle difficulty using machine learning  
- Automate dashboards (Power BI / Tableau)  

---

# 📊 Startup Expansion Analysis

This project analyzes store expansion and performance across different states using **Python** (pandas, numpy, matplotlib, seaborn) for data preprocessing, and **Power BI** for interactive dashboard visualization.

---

## 🚀 Project Workflow

### 1. Data Import & Cleaning (Python)

- Loaded the raw dataset.
- Handled missing values and inconsistencies.
- Renamed and formatted columns.
- Applied feature engineering (e.g., `Performance_State`, deviation %, below-target flag).

### 2. Preprocessing & Processing (Python)

**Statistical checks for outliers:**

- Used the standard deviation method to detect anomalies.
- Plotted histograms to visually confirm the data distribution and validate that there are no major outliers.

**New derived metrics:**

- Profit deviation percentage
- Performance categories
- Losing store indicator

**Export:** saved a cleaned dataset for visualization.

### 3. Dashboard Creation (Power BI)

Designed an interactive dashboard to explore:

- Store distribution by state
- Profit contribution by region
- Store performance segmentation
- Impact of marketing spend

---

## 📈 Dashboard Preview

The dashboard highlights:

- **KPIs:** Total Profit, Marketing Spend, Number of States, Number of Stores
- **Pie Chart:** Distribution of store performance states
- **Bar Charts:** Profit contribution by state, and performance split between losing and winning stores

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** (pandas, numpy, matplotlib, seaborn) | Data cleaning & processing |
| **Power BI** | Dashboard & visualization |

---

## 🔮 Insights & Findings

- ✅ **California** has the highest store count and profit contribution, but also a notable number of losing stores.
- ✅ Performance distribution shows a significant percentage of stores falling into "Very Poor" (-25%+).
- ✅ Marketing spend alone does not guarantee profit; performance varies significantly by state.
- ✅ The data quality check confirmed no major outliers, ensuring reliable performance insights.

---

## 📌 Next Steps

- Incorporate time-series trends (profit over time).
- Add predictive modeling for store success probability.
- Enhance geospatial visualization for store expansion planning.

---

## 📄 License

This project is released under the MIT License — feel free to use it for
learning or as a portfolio reference.

---

## 👨‍💻 Author

**Sara Ibrahim**  
*Data Scientist | Machine Learning / AI Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sara-ibrahim-omran)  
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?style=flat&logo=gmail)](mailto:Saraomran433@gmail.com)

### 🌟 Let's Connect!

I'm passionate about solving real-world problems with data, machine learning, and AI. Feel free to reach out for:

- 💼 Job opportunities and collaborations
- 📚 Technical discussions and knowledge sharing
- 🚀 Project ideas and innovative solutions

**⭐ If you find this project helpful, please give the repo a star!**
