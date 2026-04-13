# 🏏 IPL Data Analysis Project

## 📌 Project Overview

This project performs an end-to-end analysis of IPL data, progressing from basic exploratory analysis to advanced, context-driven metrics.

Beyond traditional statistics, the project introduces custom analytical frameworks such as a **Pressure Index** for evaluating clutch performance and a **Consistency Score**, enabling deeper insights into player effectiveness and match strategies.

---

## 🚀 Key Highlights

- Developed a custom **Pressure Index** to identify high-pressure situations during run chases  
- Designed **Clutch Performance metrics** to evaluate players under pressure  
- Built a refined **Consistency Score** balancing performance stability and impact  
- Performed **Phase-wise Analysis** (Powerplay, Middle, Death Overs)  
- Conducted **Team & Match Analysis** including toss impact and venue dominance  
- Implemented **SQL analysis using DuckDB**, including joins and window functions  

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy)  
- SQL (DuckDB)  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📂 Project Structure
notebooks/
01_data_cleaning.ipynb
02_eda_overview.ipynb
03_batting_analysis.ipynb
04_bowling_analysis.ipynb
05_match_analysis.ipynb
06_team_analysis.ipynb
07_advanced_analysis.ipynb
08_sql_analysis.ipynb


---

## 📊 Key Insights

- High strike rate alone does not define impact; performance under pressure is a key differentiator  
- Some high-average players show lower consistency due to variability in innings  
- Teams chasing targets often demonstrate higher win percentages  
- Death overs significantly influence match outcomes, highlighting the importance of finishers  

---

## 🧠 Advanced Analysis

### 🔥 Pressure Index
A custom metric based on:
- Required Run Rate  
- Wickets Remaining  

### ⚡ Clutch Performance
Identifies players who perform in high-pressure match situations  

### 📈 Consistency Score
Balances average performance, variability, and experience  

---

## 🧠 SQL Analysis

SQL analysis was performed using DuckDB to demonstrate:

- Aggregations (GROUP BY, HAVING)  
- Conditional logic (CASE WHEN)  
- Window functions (running totals, averages)  
- Joins combining match-level and ball-level data  

---

## 📁 Dataset

The dataset used in this project is large and not included in the repository.

You can access it here:  
https://drive.google.com/drive/folders/1oSQ33I8TlROvnGHRRYmIZNwFGJmc7mZ2

---

## 📚 Learnings

- Importance of aligning data analysis with real-world domain logic  
- Difference between basic and context-aware analysis  
- Practical use of SQL concepts like window functions and joins  
- Designing custom metrics for deeper insights  

---

## 🏁 Conclusion

This project demonstrates the ability to combine domain knowledge with data analysis to generate meaningful insights beyond standard statistics.
