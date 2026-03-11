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

## 👩‍💻 Author
**Sara Ibrahim**  
_Data Analyst | Python | SQL | Data Visualization_  

📬 Let’s connect! I’d love feedback and collaboration.  
