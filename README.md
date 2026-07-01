# Data Science & Machine Learning Portfolio

A hands-on journey through statistics, machine learning, and applied data analysis in Python — combining structured coursework with self-directed, real-world mini-projects. This repository documents both the fundamentals I've practiced and the applied problems I've solved end to end.

**Tech stack:** Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter

---

## 🔎 Highlighted Applied Projects

### E-commerce Sales Analysis — `AI prompts and ML/`
Turning raw transactional data (customers, products, orders, ratings) into revenue-focused business insight.
- **Product performance:** top products by revenue *and* by units sold — surfacing both high-margin and high-volume winners.
- **RFM customer segmentation:** scored every customer on Recency, Frequency, and Monetary value, then grouped them into actionable segments (Champions, Loyal, At Risk, Hibernating, …) to prioritise retention and revenue growth.
- **Feature engineering:** built an enriched customer table (total spend, last purchase date, review count) and product-review summaries to support downstream analysis.

### Categorical Data Imputation — `AI prompts and ML/`
Handling missing values the principled way instead of dropping or labelling them "Unknown".
- Compared **decision-tree vs. KNN** model-based imputation for a missing categorical field.
- Used **cross-validation to measure whether the imputation actually beats a naive baseline** — and reported honestly when the predictive signal was weak.
- Applied one-hot encoding and retained a "was-imputed" flag so the fill remains transparent.

---

## 📚 Fundamentals Practised

| Area | Topics |
|------|--------|
| **Regression** | Simple & multiple linear regression, dummy variables, adjusted R², feature scaling, p-values with scikit-learn |
| **Classification** | Logistic regression, binary predictors, model accuracy & testing |
| **Clustering** | K-means, choosing the number of clusters, market segmentation, categorical clustering, hierarchical clustering (heatmaps & dendrograms), species/iris segmentation |

---

## 🗂️ Repository Structure

```
.
├── AI prompts and ML/   # Applied mini-projects (sales analytics, data preprocessing) + datasets
├── Exercises/           # Guided course exercises and solutions
├── *.ipynb              # Topic notebooks (regression, logistic regression, clustering)
└── README.md
```

---

## ▶️ Running the Notebooks

```bash
git clone https://github.com/WaheedShaq/stats-and-ai-learning.git
cd stats-and-ai-learning
# With Anaconda (recommended):
jupyter notebook
```
Core dependencies: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn` (all included in a standard Anaconda install).

---

## 📫 Contact

- **LinkedIn:** _<add your LinkedIn URL here>_
- **GitHub:** [@WaheedShaq](https://github.com/WaheedShaq)

_This repository reflects ongoing learning — new projects and refinements are added as I go._
