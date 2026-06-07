# Brazilian E-Commerce Sales Analysis
### SQL + Charts + Narrative — Portfolio Project

**Python 3.8+ | SQL | Pandas | Matplotlib | Seaborn | MIT License**

---
## 🎯 Project Overview

I wanted a single project that shows how I think through a dataset end‑to‑end: from raw data to business insight. This notebook uses the *Olist Brazilian E‑Commerce* dataset — real transactions from 2016 to 2018 — to answer questions a stakeholder might actually ask. Everything is queryable, visual, and explained in plain language. No black boxes.

---

## What's Inside

I structured the notebook as a story, not a code dump. Each section starts with a business question, follows with the SQL that answers it, and finishes with a chart and a short takeaway.

| Question | Insight |
|----------|---------|
| How is revenue trending over time? | Seasonal peaks in May (Mother's Day) and November (Black Friday) |
| Which product categories drive the most revenue? | Top 3 categories account for nearly half of all income |
| Where do our highest‑value customers live? | DF (Distrito Federal) leads in average CLV |
| Do customers return after their first purchase? | Only ~30% return after Month 1 — a clear retention opportunity |
---

## 🗂️ Repository Structure

olist-sql-portfolio/
- olist_sql_charts_narrative.ipynb     (Main notebook — SQL, charts, and narrative together)
- README.md                    
---

## 📦 Data Source

**Brazilian E-Commerce Public Dataset by Olist**  
🔗 [View on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains real transactions from 2016–2018 across multiple Brazilian states, including:
- Customers, products, orders, and order items
- Timestamps, prices, and geolocation data

> *The notebook expects the dataset to be mounted at `/kaggle/input/datasets/organizations/olistbr/brazilian-ecommerce/` inside a Kaggle environment.*

---

## ⚙️ How to Run

### On Kaggle (recommended)
1. Open the notebook on [Kaggle](https://www.kaggle.com/).
2. Add the Olist dataset via the **"+ Add Data"** button.
3. Set the `DATA` path to your mounted input folder.
4. Run all cells (**Run → Run all**).

### Locally / VS Code
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/olist-sql-portfolio.git
   ```
   Install what you need:
   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```
2. Download the Olist CSVs, put them in a data/ folder, and adjust the path.
3. Open the notebook in VS Code or Jupyter and run.

The dataset is public and available on Kaggle: Brazilian E-Commerce by Olist

---

### Part 3: Skills through License

```markdown
## 🧠 Key Skills Demonstrated

| Skill | Where |
|-------|-------|
| **SQL** — CTEs, `JOIN`, `GROUP BY`, subqueries, `strftime` | Revenue trend, top categories, CLV, cohort retention |
| **Data wrangling** — `pandas` merge, rename, dropna, date parsing | Setup cell |
| **Visualisation** — `matplotlib` / `seaborn` line plots, bar charts, heatmaps | Every analysis section |
| **Dashboard** — IPython display, summary metrics | Key Metrics dashboard |
| **Cohort analysis** — retention matrix, heatmap with annotations | Cohort section |
| **Narrative storytelling** — business observations after every chart | Throughout the notebook |
---

## ✍️ Author

**Bukola Alfred**      
🔗 [GitHub](https://github.com/BAlfred-Vision/olist-sql-portfolio)

---
## About Me

I'm building a career in data analytics — I enjoy making sense of messy data and turning it into something useful. This project represents how I approach a dataset: ask clear questions, stay close to the data, and communicate results simply.

If you're reading this as a potential collaborator or employer — I'd love to walk you through the notebook in person.
🔗 [LinkedIn](https://www.linkedin.com/in/bukolaalfreddataanalyst)
```

## 📝 License

This project is licensed under the **MIT License** — feel free to reuse, adapt, and share.

---

*Built as a portfolio piece to demonstrate SQL, Python, and data storytelling in one self‑contained notebook.*