# 🚀 Product Analyst Portfolio

## English

**Data-Driven Growth Optimization for Financial Services**

This repository showcases two key projects demonstrating **end-to-end data analysis** in financial services — from hypothesis validation to pipeline implementation. Each project follows a structured approach to solve real business problems with measurable impact.

---

### 📊 Project 1: Yandex Books Hypothesis Testing & A/B Analysis

**Validating user engagement hypotheses in digital reading platform**

This project demonstrates **statistical hypothesis testing** on real-world user activity data from Yandex Books. I validated business hypotheses to optimize user engagement and conversion metrics.

#### 🔍 Key Results
| Study | Metric | Result | Significance |
|-------|--------|--------|--------------|
| **Yandex Books** | Δ avg. session time (SPb vs Moscow) | +0.38 hrs | *Not significant* (p = 0.344, power = 6.3%) |
| **BitMotion Kit** | Δ conversion rate (B vs A) | +1.59 pp (27.64% → 29.23%) | **Significant** (p = 0.0397, α = 0.05) |

> ✅ BitMotion test confirmed: new interface increased conversions by **5.75% relative**, with statistically valid design (balanced groups, no overlap, sufficient sample size).

#### 🛠️ Methodology
- **Hypothesis testing**: Welch’s t-test (robust to outliers), Mann–Whitney U-test, power analysis
- **A/B testing**: Z-test for proportions, guardrail metrics (churn, lifetime), sample size justification (α = 0.05, power = 80%)
- **Data hygiene**: Duplicate removal, cross-test contamination check, 7-day cohort windowing

#### 🧮 Technologies
- **Python**: Pandas, NumPy, SciPy, Statsmodels
- **Visualization**: Matplotlib, Seaborn
- **Statistical Framework**: A/B testing protocol with confidence intervals and effect size estimation

#### 📂 Project Structure
```
yandex_books_analysis/
├── data/
│   └── yandex_knigi_data.csv
    └── ab_test_participants.csv
    └── ab_test_events.csv.csv                
├── notebooks/
│   └── hypothesis_testing.ipynb     # Full analysis: Yandex Books + BitMotion A/B
└── README.md

---

### 🚖 Project 2: Yandex Taxi Payment Analysis

**ETL Pipeline & Aggregation for Payment Type Insights**

This project demonstrates an end-to-end data pipeline for analyzing payment methods in **Yandex Taxi**. Using Apache Spark and Airflow, I aggregated ride-level data to uncover key business metrics by payment type — enabling better financial reporting and product decisions.

#### 📊 Business Goal
Answer critical questions:
- Which payment method drives the most trips?
- What’s the average fare and tip per payment type?
- How does total revenue break down across payment options?

#### 🛠️ Tech Stack
- **Data Processing**: Apache Spark (PySpark)
- **Orchestration**: Apache Airflow (`S3KeySensor`, `DataprocCreatePysparkJobOperator`)
- **Storage**: S3 (raw Parquet), ClickHouse (aggregated results)
- **Cloud**: Yandex Cloud (Data Proc, ClickHouse)

#### 📂 Project Structure
```
yandex-taxi-payment-analysis/
└── taxi_payment_analysis.ipynb      # Full ETL logic, aggregation, and documentation
```

> 💡 *Only the notebook is published here. The actual pipeline runs on Yandex Cloud with Airflow scheduling.*

---

### 💡 Business Impact
- **Yandex Books**: Identified low statistical power as key limitation — recommended larger sample or effect-size targeting.
- **BitMotion Kit**: Validated +5.75% uplift → supported full rollout of new interface.
- **Yandex Taxi**: Enabled daily financial dashboards by payment method, helped detect anomalies, and supported product experiments.

---

*Prepared by Ivan Solovyov | March 2026*  
*Product Analyst | Data-driven growth strategy*

---

## Русский

# 🚀 Портфолио продуктового аналитика

## Данные для роста в финансовых сервисах

Этот репозиторий демонстрирует два ключевых проекта, показывающих **полный цикл анализа данных** в финансовых сервисах — от проверки гипотез до реализации пайплайна. Каждый проект следует структурированному подходу к решению реальных бизнес-задач с измеримым эффектом.

---

### 📊 Проект 1: Проверка гипотез и A/B-анализ: Яндекс Книги + BitMotion Kit

**Проверка гипотез на реальных данных цифровой платформы**

Этот проект демонстрирует **статистическую проверку гипотез** на данных пользователей сервиса «Яндекс Книги». Проверены гипотезы для оптимизации вовлечённости пользователей и конверсии.

#### 🔍 Ключевые результаты
| Исследование | Метрика | Результат | Стат. значимость |
|--------------|---------|-----------|------------------|
| **Яндекс Книги** | Δ среднего времени активности (СПб vs Москва) | +0.38 ч | *Незначимо* (p = 0.344, мощность = 6.3%) |
| **BitMotion Kit** | Δ конверсии (группа B vs A) | +1.59 п.п. (27.64% → 29.23%) | **Значимо** (p = 0.0397, α = 0.05) |

> ✅ Тест BitMotion подтверждён: новый интерфейс увеличил конверсию на **+5.75% относительно**, при корректной организации эксперимента (сбалансированные группы, нет пересечений, достаточный размер выборки).

#### 🛠️ Методология
- **Проверка гипотез**: t-тест Уэлча (устойчив к выбросам), U-тест Манна–Уитни, анализ мощности
- **A/B-тестирование**: Z-тест для пропорций, барьерные метрики (отток, лайфтайм), расчёт необходимого размера выборки (α = 0.05, мощность = 80%)
- **Очистка данных**: удаление дубликатов, проверка пересечений тестов, фильтрация по 7 дням

#### 🧮 Технологии
- **Python**: Pandas, NumPy, SciPy, Statsmodels
- **Визуализация**: Matplotlib, Seaborn
- **Статистический фреймворк**: A/B-тестирование с доверительными интервалами и расчётом эффекта

#### 📂 Структура проекта
```
yandex_books_analysis/
├── data/
│   └── yandex_knigi_data.csv
    └── ab_test_participants.csv
    └── ab_test_events.csv.csv                
├── notebooks/
│   └── hypothesis_testing.ipynb     # Full analysis: Yandex Books + BitMotion A/B
└── README.md
```

---

### 🚖 Проект 2: Анализ способов оплаты в Яндекс Такси

**ETL-пайплайн и агрегация данных для аналитики платежей**

Этот проект демонстрирует сквозной процесс обработки данных поездок в **Яндекс Такси**. С помощью Apache Spark и Airflow я агрегировал данные на уровне поездок, чтобы получить ключевые бизнес-метрики по способам оплаты — для финансовой отчётности и продуктовых решений.

#### 📊 Бизнес-цель
Ответить на ключевые вопросы:
- Какой способ оплаты генерирует больше всего поездок?
- Какова средняя стоимость поездки и чаевые по каждому типу оплаты?
- Как распределяется выручка между способами оплаты?

#### 🛠️ Используемые технологии
- **Обработка данных**: Apache Spark (PySpark)
- **Оркестрация**: Apache Airflow (`S3KeySensor`, `DataprocCreatePysparkJobOperator`)
- **Хранилища**: S3 (сырые данные в Parquet), ClickHouse (агрегированные результаты)
- **Облако**: Yandex Cloud (Data Proc, ClickHouse)

#### 📂 Структура проекта
```
yandex-taxi-payment-analysis/
└── taxi_payment_analysis.ipynb      # Полный код ETL, агрегации и пояснения
```

> 💡 *В репозитории опубликован только ноутбук. Реальный пайплайн запускается в Yandex Cloud с расписанием через Airflow.*

---

### 💡 Бизнес-эффект
- **Яндекс Книги**: Выявлена низкая статистическая мощность — рекомендовано увеличить выборку или целевой эффект.
- **BitMotion Kit**: Подтверждён +5.75% рост конверсии — обосновано полномасштабное внедрение нового интерфейса.
- **Яндекс Такси**: Ежедневные дашборды по выручке по способам оплаты, выявление аномалий, поддержка продуктовых экспериментов.

---

*Подготовил Иван Соловьев | Март 2026*  
*Продуктовый аналитик | Рост на основе данных*

Готов помочь! 🚀
