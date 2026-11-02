# 🌐 Project Portfolio - English

## 📊 Overview
This repository contains my data analysis projects focusing on **product analytics**, **A/B testing**, **web analytics automation**, **financial/cohort modeling**, and **comprehensive business assessments**. Each project demonstrates real-world application of statistical methods, API integrations, and business logic, with a focus on actionable insights for business growth.

## 📌 Projects

### 1. [Yandex Books Hypothesis Testing](yandex_books_analysis)
- **Description**: Statistical validation of user engagement hypothesis in Yandex Books service.
- **Key Results**: +12.3% uplift in user retention (p-value = 0.012), identified 2 critical funnel bottlenecks, calculated LTV/CAC ratio (3.2x ROI).
- **Technologies**: Python, Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn.

### 2. [Yandex Taxi Payment Analysis](yandex-taxi-payment-analysis)
- **Description**: ETL pipeline and aggregation for payment type insights in Yandex Taxi.
- **Key Results**: Daily financial dashboards by payment method, detection of anomalies, support for product experiments.
- **Technologies**: Apache Spark, Airflow, ClickHouse, S3.

### 3. [E-commerce Analytics & Yandex.Metrica API](ecommerce-api-analytics)
- **Description**: Full-cycle e-commerce data analysis + automated Yandex.Metrica Logs API integration.
- **Key Results**: Transactional EDA with DuckDB, data quality framework (detected 30% zero-price items), automated API pipeline (auth → log request → download → Excel report).
- **Technologies**: Python, Pandas, DuckDB, Requests, OpenPyXL, Yandex.Metrica Logs API.

### 4. [KION Subscription Base Analysis](kion-subscription-analysis)
- **Description**: Comprehensive cohort analysis, retention tracking, and 24-month forecasting for a major video streaming service. Successfully defended at the final interview stage.
- **Key Results**: Identified critical churn points (months 3-4, 10-11), revealed 43% viewing activity among 98% paying users ("sleeping" subscribers), built a decay-rate projection model.
- **Technologies**: Microsoft Excel (Advanced modeling, Pivot Tables, Cohort Matrices), Data Quality validation, Scenario forecasting.

### 5. [Sberbank SQL & Business Logic Assessment](sber-sql-python-assessment)
- **Description**: Multi-faceted analytical assessment for Sberbank covering SQL segmentation, executive visualization, market hypothesis testing (GMV March 2022), and Python ETL automation. Successfully defended with the hiring manager.
- **Key Results**: Built 3-chart executive dashboard for salary distribution, formulated 5 hypotheses for +15% GMV spike, automated raw log parsing for contract IDs.
- **Technologies**: SQL (CTEs, Window Functions, CASE), Python (Pandas, Matplotlib, Seaborn, Glob), Data Quality, Executive Reporting.

## 📂 Repository Structure
```text
my_projects/
├── yandex_books_analysis/
│   ├── data/
│   ├── notebook/
│   └── README.md
├── yandex-taxi-payment-analysis/
│   └── notebook/
│   └── README.md
├── ecommerce-api-analytics/
│   ├── purchases.csv
│   ├── products.csv
│   ├── Part_1_Data_Analysis.ipynb
│   ├── Part_2_API_Report.ipynb
│   └── README.md
├── kion-subscription-analysis/
│   ├── data.csv
│   ├── KION_Calculations.xlsx
│   ├── KION_Analysis_Report.pdf
│   └── README.md
├── sber-sql-python-assessment/
│   ├── Sber_SQL_Python_Assessment.ipynb
│   ├── data_for_test.txt
│   ├── Тест_Python.docx
│   ├── Тест_SQL_логика_2510.docx
│   └── README.md
└── README.md
```

## 🛠️ How to Use
1. Clone the repository: `git clone https://github.com/yourusername/my_projects.git`
2. Navigate to project directory: `cd my_projects/<project-name>`
3. Install dependencies: `pip install -r requirements.txt` (if available) or see project README
4. Run Jupyter notebooks or review Excel/PDF reports as described in each project's documentation.

## 🌟 About Me
I am a Data/Product Analyst with **4+ years of domain experience in the Banking and Finance sector**. I specialize in turning complex data into actionable business decisions through A/B testing, funnel optimization, cohort analysis, and unit economics. Currently deepening expertise in advanced experimentation methods and causal inference.

---

# 🌐 Портфолио проектов - Русский

## 📊 Обзор
Этот репозиторий содержит мои проекты по анализу данных в области **продуктовой аналитики**, **A/B-тестирования**, **автоматизации веб-аналитики**, **финансового/когортного моделирования** и **комплексных бизнес-оценок**. Каждый проект демонстрирует практическое применение статистических методов и бизнес-логики с акцентом на получение измеримых результатов для бизнеса.

## 📌 Проекты

### 1. [Проверка гипотез в Яндекс Книгах](yandex_books_analysis)
- **Описание**: Статистическая проверка гипотезы об активности пользователей в сервисе Яндекс Книги.
- **Ключевые результаты**: +12.3% рост удержания пользователей (p-value = 0.012), выявлено 2 критических узких места в воронке, рассчитано соотношение LTV/CAC (3.2x ROI).
- **Технологии**: Python, Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn.

### 2. [Анализ платежей в Яндекс Такси](yandex-taxi-payment-analysis)
- **Описание**: ETL-пайплайн и агрегация данных по способам оплаты в Яндекс Такси.
- **Ключевые результаты**: Ежедневные финансовые дашборды, обнаружение аномалий, поддержка продуктовых экспериментов.
- **Технологии**: Apache Spark, Airflow, ClickHouse, S3.

### 3. [Аналитика e-commerce и API Яндекс.Метрики](ecommerce-api-analytics)
- **Описание**: Полный цикл анализа e-commerce данных + автоматизация API Яндекс.Метрики Logs API.
- **Ключевые результаты**: EDA транзакционных данных через DuckDB, фреймворк качества данных (обнаружены 30% товаров с нулевой ценой), автоматизированный API-пайплайн (авторизация → запрос логов → скачивание → генерация Excel-отчета).
- **Технологии**: Python, Pandas, DuckDB, Requests, OpenPyXL, Яндекс.Метрика Logs API.

### 4. [Анализ и прогнозирование подписочной базы KION](kion-subscription-analysis)
- **Описание**: Комплексный когортный анализ, трекинг удержания и прогнозирование на 24 месяца для крупного видеосервиса. Успешно защищен на финальном этапе собеседования.
- **Ключевые результаты**: Выявлены критические точки оттока (3-4 и 10-11 мес.), обнаружено падение вовлеченности до 43% при 98% оплат ("спящие" подписчики), построена модель прогноза на основе темпов распада когорт.
- **Технологии**: Microsoft Excel (продвинутое моделирование, сводные таблицы, когортные матрицы), валидация качества данных, сценарное прогнозирование.

### 5. [Комплексная оценка для Сбербанка](sber-sql-python-assessment)
- **Описание**: Многокомпонентное аналитическое тестовое задание для Сбербанка: SQL-сегментация, управленческая визуализация, проверка гипотез роста GMV (март 2022) и автоматизация ETL на Python. Успешно защищено перед нанимающим руководителем.
- **Ключевые результаты**: Создан 3-графиковый дашборд распределения зарплат для руководства, сформулированы 5 гипотез роста GMV на +15%, автоматизирован парсинг сырых логов для извлечения ID контрактов.
- **Технологии**: SQL (CTE, оконные функции, CASE), Python (Pandas, Matplotlib, Seaborn, Glob), контроль качества данных, управленческая отчетность.

## 📂 Структура репозитория
```text
my_projects/
├── yandex_books_analysis/
│   ├── data/
│   ├── notebook/
│   └── README.md
├── yandex-taxi-payment-analysis/
│   └── notebook/
│   └── README.md
├── ecommerce-api-analytics/
│   ├── purchases.csv
│   ├── products.csv
│   ├── Part_1_Data_Analysis.ipynb
│   ├── Part_2_API_Report.ipynb
│   └── README.md
├── kion-subscription-analysis/
│   ├── data.csv
│   ├── KION_Calculations.xlsx
│   ├── KION_Analysis_Report.pdf
│   └── README.md
├── sber-sql-python-assessment/
│   ├── Sber_SQL_Python_Assessment.ipynb
│   ├── data_for_test.txt
│   ├── Тест_Python.docx
│   ├── Тест_SQL_логика_2510.docx
│   └── README.md
└── README.md
```

## 🛠️ Как использовать
1. Клонируйте репозиторий: `git clone https://github.com/yourusername/my_projects.git`
2. Перейдите в директорию проекта: `cd my_projects/<имя-проекта>`
3. Установите зависимости: `pip install -r requirements.txt` (если есть) или см. README проекта
4. Запустите Jupyter-ноутбуки или изучите Excel/PDF отчеты согласно документации каждого проекта.

## 🌟 Обо мне
Я — аналитик данных с **4+ годами предметного опыта в банковском и финансовом секторе**. Специализируюсь на превращении сложных данных в конкретные бизнес-решения через A/B-тестирование, оптимизацию воронок, когортный анализ и юнит-экономику. Сейчас углубляю экспертизу в продвинутых методах экспериментов и причинно-следственном анализе.
