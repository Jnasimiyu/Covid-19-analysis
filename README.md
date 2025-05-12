# Covid-19-analysis
# 🌍 COVID-19 Country-Wise Data Analysis

This project is a data exploration and visualization of global COVID-19 statistics using a dataset named `country_wise_latest.csv`. The analysis was performed in a Jupyter Notebook and includes data cleaning, statistical summaries, and various charts to better understand the impact of COVID-19 on a country level.

---

## Objectives

- Load and explore country-level COVID-19 data
- Clean missing or inconsistent data entries
- Compute descriptive statistics (mean, median, standard deviation, etc.)
- Visualize key metrics such as Confirmed cases, Deaths, Recovered cases, and Death Rate
- Compare countries using visual tools (bar, line, histogram, scatter, pie, and donut charts)
- Derive insights from visual patterns and trends

---

Tools & Libraries Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data loading and manipulation
- **Matplotlib** – Basic visualizations
- **Seaborn** – Advanced and aesthetic plotting

---
 ▶️ How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Jnasimiyu/covid-country-analysis.git
   cd covid-country-analysis
Install required packages (if not already installed):

pip install pandas matplotlib seaborn
Start Jupyter Notebook:


Open and run the notebook file named covid_analysis.ipynb.

⚠️ Make sure the file country_wise_latest.csv is in the same directory as the notebook.

📊 Visualizations Included
✅ Bar Chart (Top 10 countries by Confirmed Cases and Deaths)

✅ Line Chart (Confirmed vs Recovered cases)

✅ Histogram (Distribution of Deaths)

✅ Scatter Plot (Confirmed vs Recovered)

✅ Pie Chart (Top and Bottom 5 countries by Deaths)

✅ Donut Chart (Same as pie with inner radius)

🔍 Insights & Reflections
The top 10 countries by confirmed cases account for a large proportion of global COVID-19 cases.

There is a high positive correlation between Confirmed and Recovered cases.

Smaller or less affected countries had disproportionately high Death Rates when population was considered.

Pie charts helped in presenting proportional impacts visually.

This project enhanced understanding of real-world data cleaning and visual storytelling with Python.

📁 Folder Structure
Copy
Edit
📦 covid-country-analysis
├── 📄 country_wise_latest.csv
├── 📔 covid_analysis.ipynb

📌 Acknowledgments
Dataset: country_wise_latest.csv (typically from Kaggle)

Libraries: Pandas, Matplotlib, Seaborn

Inspired by global data analysis needs during the pandemic

🧠 Future Work (Optional Ideas)
Time-series visualization if time-based data is added

Interactive dashboard with Plotly or Dash

Machine learning to predict case growth or death rates


