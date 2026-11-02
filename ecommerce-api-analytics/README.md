# 📊 E-commerce Analytics & Yandex.Metrica API Integration - English

## 📋 Overview
This project demonstrates a full-cycle data analysis pipeline for an e-commerce platform and integration with the Yandex.Metrica Logs API. It covers data exploration, anomaly detection, API automation, and reporting best practices. The goal is to transform raw transactional and web analytics data into actionable business insights while ensuring data quality.

## 🔍 Key Tasks Solved
1. **Transactional Data Analysis**: Analyzed purchase behavior using Pandas and DuckDB. Identified key traffic sources, daily sales trends, and product performance metrics.
2. **Data Quality Assessment**: Detected critical anomalies including zero-price items (~30% of catalog) and incomplete data dumps, establishing validation rules for future pipelines.
3. **Yandex.Metrica API Automation**: Built a Python script to authenticate, request logs, wait for processing, download raw visit data, and generate formatted Excel reports automatically.
4. **Business Recommendations**: Proposed RFM segmentation, funnel depth analysis by source, and automated alerting systems for bounce rates and data gaps.

## 🛠️ Technologies & Tools
- **Languages**: Python 3.x, SQL (DuckDB)
- **Libraries**: Pandas, Matplotlib, Requests, OpenPyXL
- **APIs**: Yandex.Metrica Logs API
- **Concepts**: EDA, Data Quality Checks, API Rate Limiting, Automated Reporting

## 📂 Project Structure
```
ecommerce-api-analytics/
├── purchases.csv # Transactional data (6k+ rows)
├── products.csv # Product catalog data (20k+ rows)
├── Part_1_Data_Analysis.ipynb # EDA, visualization, SQL queries via DuckDB
├── Part_2_API_Report.ipynb # Yandex.Metrica API integration & report generation
└── README.md
```

## 🚀 How to Run
1. Clone repository and navigate to folder: `cd ecommerce-api-analytics`
2. Install dependencies: `pip install pandas matplotlib requests openpyxl duckdb`
3. For API part: Create `yandex_oauth_token.txt` with your OAuth token
4. Run notebooks sequentially:
   - `Part_1_Data_Analysis.ipynb` for transactional insights
   - `Part_2_API_Report.ipynb` for web analytics automation

## 💡 Key Insights
- Source `direct` has highest average check (5803 ₽), while `social` is lowest (2683 ₽)
- ~30% of products have zero price (likely bonus/technical items) requiring filtering
- Incomplete data dump detected for June 1st, 2025 – requires retry logic in production

---

# 📊 Аналитика e-commerce и интеграция с API Яндекс.Метрики - Русский

## 📋 Обзор
Проект демонстрирует полный цикл анализа данных для e-commerce платформы и автоматизацию работы с API Яндекс.Метрики. Включает разведочный анализ, обнаружение аномалий, автоматизацию выгрузки логов и формирование отчетности. Цель — превращение сырых транзакционных и веб-аналитических данных в бизнес-инсайты при обеспечении качества данных.

## 🔍 Решенные задачи
1. **Анализ транзакционных данных**: Исследование покупательского поведения с помощью Pandas и DuckDB. Определение ключевых источников трафика, динамики продаж и эффективности товаров.
2. **Оценка качества данных**: Выявление критических аномалий, включая товары с нулевой ценой (~30% каталога) и неполные выгрузки данных. Разработка правил валидации для пайплайнов.
3. **Автоматизация API Яндекс.Метрики**: Создание Python-скрипта для авторизации, создания запроса логов, ожидания обработки, скачивания сырых данных и генерации Excel-отчетов.
4. **Бизнес-рекомендации**: Предложены RFM-сегментация, анализ глубины воронки по источникам и система алертинга для отказов и пропусков данных.

## 🛠️ Технологии и инструменты
- **Языки**: Python 3.x, SQL (DuckDB)
- **Библиотеки**: Pandas, Matplotlib, Requests, OpenPyXL
- **API**: Яндекс.Метрика Logs API
- **Концепции**: EDA, проверки качества данных, лимиты API, автоматическая отчетность

## 📂 Структура проекта
```
ecommerce-api-analytics/
├── purchases.csv # Транзакционные данные (6k+ строк)
├── products.csv # Каталог товаров (20k+ строк)
├── Часть_1_Анализ_данных.ipynb # EDA, визуализация, SQL через DuckDB
├── Часть_2_API_Отчетность.ipynb # Интеграция с API и генерация отчетов
└── README.md
```
## 🚀 Как запустить
1. Клонируйте репозиторий и перейдите в папку: `cd ecommerce-api-analytics`
2. Установите зависимости: `pip install pandas matplotlib requests openpyxl duckdb`
3. Для части с API: создайте файл `yandex_oauth_token.txt` с вашим OAuth-токеном
4. Запустите ноутбуки последовательно:
   - `Часть_1_Анализ_данных.ipynb` для транзакционных инсайтов
   - `Часть_2_API_Отчетность.ipynb` для автоматизации веб-аналитики

## 💡 Ключевые выводы
- Источник `direct` имеет самый высокий средний чек (5803 ₽), `social` — самый низкий (2683 ₽)
- ~30% товаров имеют нулевую цену (вероятно, бонусные/технические позиции), требуют фильтрации
- Обнаружена неполная выгрузка данных за 1 июня 2025 г. — необходима логика повторных запросов в продакшене
