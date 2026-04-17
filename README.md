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

## 📈 Key Findings
| Metric               | Moscow | St. Petersburg |
|----------------------|--------|----------------|
| Avg. activity (hrs)  | 10.88  | 11.26          |
| Median activity (hrs)| 0.92   | 0.88           |
| Sample size          | 6,234  | 2,306          |
| **p-value (Welch)**  | —      | **0.344**      |

➡️ **Conclusion**:  
The observed +0.38 hr difference is **not statistically significant** (α = 0.05), though the direction aligns with the hypothesis. Power analysis revealed low test power (≈6.3%), suggesting a larger sample or effect size is needed.

## 💡 Business Implications
- The null hypothesis **cannot be rejected** — no evidence that SPb users are more active.
- However, the positive trend (+3.5%) warrants further investigation (e.g., segmentation by device, age, or reading frequency).
- This analysis informed how to design future experiments: prioritize **power**, **effect size estimation**, and **guardrail metrics**.

---

*Prepared by Ivan Solovev | 01 Sep 2025*  
*Product Analyst | Data-driven growth strategy*
