# 🎬 TMDb Movie Data Analysis

This project is a **data analysis of 5,000 movies sourced from TMDb (The Movie Database)**.  
Using **Python, pandas, matplotlib, and seaborn**, the project explores how **popularity, budget, and genres** influence movie revenues.  

---
## 📌 The analysis focuses on three key question:
- Do movies with **high popularity** achieve **high revenue**?  
- What are the most **filmed genres** in the dataset?  
- Is there a **correlation between budget and revenue**?  
---

## ⚙️ Setup Instructions

1. Clone the repository:
   git clone https://github.com/Amuruth6/tmdb-movie-data-analysis.git
2. Install required dependencies:
   pip install -r requirements.txt
3. Launch Jupyter Notebook:
   jupyter notebook
4. Open tmdb_DataAnalysis.ipynb and run the cells to reproduce the analysis.
---

🛠️ Problem Faced & Solution

Issue: The genres column contained values stored as string representations of lists (e.g., "[{'id': 18, 'name': 'Drama'}]").

Fix: Used Python’s ast.literal_eval to safely convert strings into Python lists for further analysis.

📊 Key Insights

Popularity vs Revenue → Higher popularity often leads to higher revenue, but not always. Some movies gained popularity but underperformed financially.

Most Filmed Genres → Drama, Comedy, and Action were the most common genres in the dataset.

Budget vs Revenue Correlation → Strong positive correlation: higher budgets generally result in higher revenues.

🚀 Future Improvements

Add year-wise analysis of revenue and popularity trends.

Build predictive models (regression/ML) to estimate movie revenue.

Create interactive dashboards using Plotly or Power BI.

## 📝 License
This project is licensed under the MIT License.  
Dataset source: [TMDb](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) (for educational purposes only).
   cd tmdb-movie-data-analysis

