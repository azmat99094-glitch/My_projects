# 🌐 Project Portfolio - English

## 📊 Overview
This repository contains my data analysis projects for **product analytics** and **A/B testing**. Each project demonstrates real-world application of statistical methods in digital product analytics, with a focus on actionable insights for business growth.

## 📌 Projects

### 1. [Yandex Books Hypothesis Testing](yandex_books_analysis)
- **Description**: Statistical validation of user engagement hypothesis in Yandex Books service
- **Key Results**: 
  - +12.3% uplift in user retention (p-value = 0.012)
  - Identified 2 critical funnel bottlenecks
  - Calculated LTV/CAC ratio (3.2x ROI)
- **Technologies**: Python, Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn

### 2. [Yandex Taxi Payment Analysis](yandex-taxi-payment-analysis)
- **Description**: ETL pipeline and aggregation for payment type insights in Yandex Taxi
- **Key Results**:
  - Daily financial dashboards by payment method
  - Detection of anomalies (e.g., sudden drop in card payments)
  - Support for product experiments (e.g., promoting cashless payments)
- **Technologies**: Apache Spark, Airflow, ClickHouse, S3

### 3. [E-commerce Analytics & Yandex.Metrica API](ecommerce-api-analytics)
- **Description**: Full-cycle e-commerce data analysis + automated Yandex.Metrica Logs API integration
- **Key Results**:
  - Transactional EDA with DuckDB: identified top-performing traffic sources (`direct`: 5803₽ avg check)
  - Data Quality framework: detected 30% zero-price items and incomplete dumps, proposed validation rules
  - Automated API pipeline: auth → log request → processing wait → download → Excel report generation
  - Business recommendations: RFM segmentation, funnel depth analysis, automated alerting system
- **Technologies**: Python, Pandas, DuckDB, Requests, OpenPyXL, Yandex.Metrica Logs API

## 📂 Repository Structure
```
my_projects/
├── yandex_books_analysis/
│ ├── data/
│ ├── notebook/
│ └── README.md
├── yandex-taxi-payment-analysis/
│ └── notebook/
│ └── README.md
├── ecommerce-api-analytics/
│ ├── purchases.csv
│ ├── products.csv
│ ├── Part_1_Data_Analysis.ipynb
│ ├── Part_2_API_Report.ipynb
│ └── README.md
└── README.md
```

## 🛠️ How to Use
1. Clone the repository: `git clone https://github.com/yourusername/my_projects.git`
2. Navigate to project directory: `cd my_projects/<project-name>`
3. Install dependencies: `pip install -r requirements.txt` (if available) or see project README
4. Run Jupyter notebooks as described in each project's documentation

## 🌟 About Me
I am a Data/Product Analyst with **4+ years of domain experience in the Banking and Finance sector**. I specialize in turning complex data into actionable business decisions through A/B testing, funnel optimization, and unit economics. Currently deepening expertise in advanced experimentation methods (CUPED, stratification) and causal inference.

---

# 🌐 Портфолио проектов - Русский

## 📊 Обзор
Этот репозиторий содержит мои проекты по анализу данных в области **продуктовой аналитики** и **A/B-тестирования**. Каждый проект демонстрирует практическое применение статистических методов в цифровой аналитике, с акцентом на получение бизнес-ориентированных результатов.

## 📌 Проекты

### 1. [Проверка гипотез в Яндекс Книгах](yandex_books_analysis)
- **Описание**: Статистическая проверка гипотезы об активности пользователей в сервисе Яндекс Книги
- **Ключевые результаты**:
  - +12.3% рост удержания пользователей (p-value = 0.012)
  - Выявлено 2 критических узких места в воронке
  - Расчитано соотношение LTV/CAC (3.2x ROI)
- **Технологии**: Python, Pandas, NumPy, SciPy, Statsmodels, Matplotlib, Seaborn

### 2. [Анализ платежей в Яндекс Такси](yandex-taxi-payment-analysis)
- **Описание**: ETL-пайплайн и агрегация данных по способам оплаты в Яндекс Такси
- **Ключевые результаты**:
  - Ежедневные финансовые дашборды по способам оплаты
  - Обнаружение аномалий (например, резкое падение оплат картой)
  - Поддержка продуктовых экспериментов (например, продвижение бесконтактных платежей)
- **Технологии**: Apache Spark, Airflow, ClickHouse, S3

### 3. [Аналитика e-commerce и API Яндекс.Метрики](ecommerce-api-analytics)
- **Описание**: Полный цикл анализа e-commerce данных + автоматизация API Яндекс.Метрики Logs API
- **Ключевые результаты**:
  - EDA транзакционных данных через DuckDB: определены топ-источники трафика (`direct`: ср. чек 5803₽)
  - Фреймворк качества данных: обнаружены 30% товаров с нулевой ценой и неполные выгрузки, предложены правила валидации
  - Автоматизированный API-пайплайн: авторизация → запрос логов → ожидание обработки → скачивание → генерация Excel-отчета
  - Бизнес-рекомендации: RFM-сегментация, анализ глубины воронки, система автоматического алертинга
- **Технологии**: Python, Pandas, DuckDB, Requests, OpenPyXL, Яндекс.Метрика Logs API

## 📂 Структура репозитория
```
my_projects/
├── yandex_books_analysis/
│ ├── data/
│ ├── notebook/
│ └── README.md
├── yandex-taxi-payment-analysis/
│ └── notebook/
│ └── README.md
├── ecommerce-api-analytics/
│ ├── purchases.csv
│ ├── products.csv
│ ├── Part_1_Data_Analysis.ipynb
│ ├── Part_2_API_Report.ipynb
│ └── README.md
└── README.md
```

## 🛠️ Как использовать
1. Клонируйте репозиторий: `git clone https://github.com/yourusername/my_projects.git`
2. Перейдите в директорию проекта: `cd my_projects/<имя-проекта>`
3. Установите зависимости: `pip install -r requirements.txt` (если есть) или см. README проекта
4. Запустите Jupyter-ноутбуки согласно документации каждого проекта

## 🌟 Обо мне
Я — аналитик данных с **4+ годами предметного опыта в банковском и финансовом секторе**. Специализируюсь на превращении сложных данных в конкретные бизнес-решения через A/B-тестирование, оптимизацию воронок и юнит-экономику. Сейчас углубляю экспертизу в продвинутых методах экспериментов (CUPED, стратификация) и причинно-следственном анализе.

