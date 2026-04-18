# 📊 Hypothesis Testing & A/B Analysis: Yandex Books + BitMotion Kit

**Data-Driven Product Analysis for Growth Optimization**

This project demonstrates end-to-end statistical validation in digital product analytics — from hypothesis testing on real-world user activity data to rigorous A/B test evaluation for conversion optimization.

## 🔍 Key Results
| Study | Metric | Result | Significance |
|-------|--------|--------|--------------|
| **Yandex Books** | Δ avg. session time (SPb vs Moscow) | +0.38 hrs | *Not significant* (p = 0.344, power = 6.3%) |
| **BitMotion Kit** | Δ conversion rate (B vs A) | +1.59 pp (27.64% → 29.23%) | **Significant** (p = 0.0397, α = 0.05) |

> ✅ BitMotion test confirmed: new interface increased conversions by **5.75% relative**, with statistically valid design (balanced groups, no overlap, sufficient sample size).

## 🛠️ Methodology
- **Hypothesis testing**: Welch’s t-test (robust to outliers), Mann–Whitney U-test, power analysis
- **A/B testing**: Z-test for proportions, guardrail metrics (churn, lifetime), sample size justification (α = 0.05, power = 80%)
- **Data hygiene**: Duplicate removal, cross-test contamination check, 7-day cohort windowing

## 🧮 Technologies
- **Python**: Pandas, NumPy, SciPy, Statsmodels
- **Visualization**: Matplotlib, Seaborn
- **Statistical Framework**: A/B testing protocol with confidence intervals and effect size estimation

## 📂 Project Structure
yandex_books_analysis/
├── data/
│ └── raw_data.csv
  └── ab_test_participants.csv
  └── ab_test_events.csv
├── notebooks/
│ └── hypothesis_testing.ipynb # Full analysis: Yandex Books + BitMotion A/B
└── README.md

## 💡 Business Impact
- For Yandex Books: Identified low statistical power as key limitation — recommended larger sample or effect-size targeting.
- For BitMotion Kit: Validated +5.75% uplift → supported full rollout of new interface.

---

*Prepared by Ivan Solovev | 01 Sep 2025*  
*Product Analyst | Data-driven growth strategy*
