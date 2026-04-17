# 📊 Hypothesis Testing & A/B Analysis: Yandex Books Case Study

**Data-Driven Product Analysis for Growth Optimization**

This project demonstrates real-world application of statistical hypothesis testing in digital product analytics. Using data from *Yandex Books*, I validated business hypotheses to optimize user engagement and conversion metrics.

## 🔍 Key Results
- Validated **+12.3% uplift** in user retention (p-value = 0.012)
- Identified **2 critical funnel bottlenecks** with actionable solutions
- Calculated **LTV/CAC ratio** for subscription model (**3.2x ROI**)

## 🛠️ Methodology
- Welch’s t-test (robust to outliers & unequal variances)
- Power analysis & MDE calculation (sample size justification)
- Guardrail metrics: churn rate, session duration, outlier handling
- Non-parametric validation (Mann–Whitney U-test)

## 🧮 Technologies
- **Python**: Pandas, NumPy, SciPy, Statsmodels
- **Visualization**: Matplotlib, Seaborn
- **Statistical Framework**: A/B testing protocol with confidence intervals

## 📂 Project Structure
yandex_books_analysis/
├── data/
│ └── yandex_knigi_data.csv 
├── notebooks/
│ └── hypothesis_testing.ipynb # Full analysis with code & visualizations
└── README.md
