# 🏠 House Prices — Seaborn Visualizations & Analysis

A data visualization project exploring the **House Prices dataset** using Python and Seaborn. Includes two notebooks covering Seaborn fundamentals and in-depth house price analysis.

---

## 📁 Dataset

- **train.csv** — House Prices dataset with 1,460 rows and 81 columns
  - Key features: `Neighborhood`, `GrLivArea`, `HouseStyle`, `SaleType`, `OverallQual`
  - Target variable: `SalePrice`

---

## 📓 Notebooks

### 1. `sea2_fixed.ipynb` — Seaborn Fundamentals
Covers core Seaborn concepts using built-in datasets (tips, titanic, iris, car_crashes):
- Seaborn styles: `dark`, `ticks`, `darkgrid`, `whitegrid`
- `relplot` — scatter & line plots
- `histplot` — distribution plots
- `barplot`, `countplot`, `pointplot`
- `jointplot` — bivariate distribution
- Multi-plot dashboards with `subplots`

### 2. `seaborn_fixed.ipynb` — House Prices Analysis
In-depth visualizations on the House Prices dataset:
- 📊 Average Sale Price by Neighborhood (sorted bar chart)
- 🔵 Sale Price vs Living Area (scatter plot)
- 📈 Sale Price Distribution (histogram + KDE)
- 📦 Sale Price by House Style (box plot)
- 📉 Line plot: Avg Sale Price by Neighborhood
- 🏷️ Avg Sale Price by Sale Type
- 🔥 Correlation Heatmap (top 10 features vs SalePrice)

---

## 📊 Key Findings

| Insight | Detail |
|---------|--------|
| Top Neighborhood | `NoRidge` has the highest average sale price |
| Strongest Correlator | `OverallQual` is most correlated with `SalePrice` |
| Price Distribution | Right-skewed — most homes priced between $100k–$250k |
| Best House Style | `2Story` homes tend to have higher sale prices |

---

## 🛠️ Libraries Used

```
pandas
seaborn
matplotlib
```

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/Nayan0223/house-prices-seaborn-analysis.git
```

2. Install dependencies:
```bash
pip install pandas seaborn matplotlib
```

3. Open either notebook:
```bash
jupyter notebook seaborn_fixed.ipynb
jupyter notebook sea2_fixed.ipynb
```

---


---

## 👤 Author

**Nayan0223**  
GitHub: [@Nayan0223](https://github.com/Nayan0223)
