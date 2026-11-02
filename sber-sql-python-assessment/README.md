# 🏦 Sberbank Comprehensive Analytical Assessment - English

## 📋 Overview
A multi-faceted analytical assessment completed for Sberbank, demonstrating end-to-end data skills: from advanced SQL querying and Python ETL automation to business hypothesis generation and executive reporting. The project was successfully defended in person with the hiring manager.

## 🔍 Project Structure

### Part 1: SQL Analytics (5 Tasks + Creative Assignment)
Complex SQL queries using CTEs, JOINs, CASE statements, and window functions to analyze client data across territorial banks.

**Tasks Completed:**
1. **Client Distribution by Bank:** Filtered clients with POS turnover ≥ 1000 RUB, grouped by territorial bank.
2. **Age-Based Metrics:** Calculated average salary and POS turnover segmented by customer age.
3. **Demographic Segmentation:** Built both pivot-table and long-format views of client distribution by bank and age group (<18, 18-30, 30-60, 60+).
4. **Above-Average Performers:** Identified clients with POS turnover exceeding the portfolio average using subqueries.
5. **Executive Salary Distribution Slide (Creative):** Translated a vague managerial request into a comprehensive 3-chart analytical dashboard:
   - Histogram of salary segments with percentage shares
   - Box plot of salaries by territorial bank (showing regional disparities)
   - Scatter plot of salary vs. POS turnover (revealing correlation patterns)

### Part 2: Business Analysis - GMV Marketplace Hypotheses
Structured analysis of a +15% GMV spike in March 2022, with 5 detailed hypotheses:
1. **Panic Buying (60-70% of growth):** Geopolitical uncertainty, ruble devaluation, stockpiling behavior
2. **Low Base Effect (20-30%):** Statistical rebound from January's -29% decline
3. **Traffic Redistribution (10-20%):** Migration from departing international retailers (IKEA, H&M, Zara)
4. **Inflation Expectations:** Accelerated purchases before anticipated price hikes
5. **Seasonal Factors:** End-of-Q1 B2B procurement and spring preparation

**Key Insight:** The growth was temporary and unsustainable, confirmed by April's -4% decline due to supply chain disruptions and assortment shrinkage (electronics -42.3%).

### Part 3: Python ETL & Data Quality
Automated processing of raw web analytics logs:
1. **Tasks 1-2:** Parsed `eventLabel` fields to extract contract numbers, added processing dates, and exported structured data to semicolon-delimited TXT files.
2. **Task 3 (Advanced):** Implemented automated file discovery using `glob` and `os.path.getmtime` to identify and process the most recent data file in a directory with historical archives.

## 🛠️ Technologies
- **SQL:** SQLite, CTEs, Window Functions, CASE logic, Subqueries, Aggregations
- **Python:** Pandas, Matplotlib, Seaborn, Glob, OS, Datetime
- **Concepts:** Business Intelligence, Data Segmentation, Executive Reporting, ETL Pipelines, Data Quality, Market Hypothesis Testing

## 📂 Project Structure
'''
sber-sql-python-assessment/
├── Sber_SQL_Python_Assessment.ipynb # Unified notebook with all tasks and visualizations
├── data_for_test.txt # Raw source data for Python ETL tasks
├── Тест_Python.docx # Original Python task specifications
├── Тест_SQL_логика_2510.docx # Original SQL task specifications
└── README.md
'''

## 💡 Key Business Insights
- **Portfolio Imbalance:** 72% of clients fall into "Low" and "Medium" salary segments but generate disproportionate portfolio value in "High" and "Premium" tiers.
- **Regional Strategy:** Юго-Западный банк shows the widest salary dispersion (10k-150k RUB), requiring differentiated product strategies.
- **Cross-Sell Opportunity:** Московский банк clients with ~30k salary demonstrate anomalously high POS turnover (35k), indicating credit product potential.
- **Market Dynamics:** March 2022 GMV growth was primarily panic-driven (60-70%), not organic demand expansion.

## 🎯 Outcome
Successfully completed all technical tasks and defended the analytical findings with the hiring manager. The project demonstrates the ability to translate abstract business requests into structured data solutions and actionable insights.

---

# 🏦 Комплексная аналитическая оценка для Сбербанка - Русский

## 📋 Обзор
Многокомпонентное аналитическое тестовое задание для Сбербанка, демонстрирующее сквозные навыки работы с данными: от продвинутого SQL и автоматизации ETL на Python до генерации бизнес-гипотез и управленческой отчетности. Проект успешно защищен лично перед нанимающим руководителем.

## 🔍 Структура проекта

### Часть 1: SQL-аналитика (5 задач + творческое задание)
Сложные SQL-запросы с использованием CTE, JOIN, CASE и оконных функций для анализа клиентской базы по территориальным банкам.

**Выполненные задачи:**
1. **Распределение клиентов по банкам:** Фильтрация клиентов с POS-оборотом ≥ 1000 руб., группировка по территориальным банкам.
2. **Метрики по возрасту:** Расчет средней зарплаты и POS-оборота в разрезе возраста клиентов.
3. **Демографическая сегментация:** Построение pivot-таблицы и нормализованного формата распределения клиентов по банкам и возрастным группам (<18, 18-30, 30-60, 60+).
4. **Клиенты выше среднего:** Выявление клиентов с POS-оборотом выше среднего по базе с использованием подзапросов.
5. **Слайд для руководства (творческое):** Трансляция абстрактного запроса «вывести распределение по зарплате» в комплексный аналитический дашборд из 3 графиков:
   - Гистограмма зарплатных сегментов с процентными долями
   - Box plot зарплат по территориальным банкам (выявление региональных различий)
   - Scatter plot связи зарплаты и POS-оборота (выявление корреляционных паттернов)

### Часть 2: Бизнес-анализ - Гипотезы роста GMV маркетплейсов
Структурированный анализ роста GMV на +15% в марте 2022 года с 5 детальными гипотезами:
1. **Ажиотажный спрос (60-70% роста):** Геополитическая неопределенность, девальвация рубля, панические закупки
2. **Эффект низкой базы (20-30%):** Статистический отскок от падения января (-29%)
3. **Перераспределение трафика (10-20%):** Миграция потребителей с ушедших международных ритейлеров (IKEA, H&M, Zara)
4. **Инфляционные ожидания:** Ускорение покупок перед ожидаемым ростом цен
5. **Сезонный фактор:** Закрытие квартала и B2B-закупки

**Ключевой вывод:** Рост носил временный характер, что подтвердилось падением в апреле (-4%) из-за разрыва цепочек поставок и сокращения ассортимента (электроника -42.3%).

### Часть 3: Python ETL и контроль качества данных
Автоматизированная обработка сырых логов веб-аналитики:
1. **Задания 1-2:** Парсинг полей `eventLabel` для извлечения номеров контрактов, добавление дат обработки и экспорт структурированных данных в TXT-файлы с разделителем «;».
2. **Задание 3 (повышенной сложности):** Реализация автоматического обнаружения файлов через `glob` и `os.path.getmtime` для идентификации и обработки наиболее актуального файла в директории с историей архивов.

## 🛠️ Технологии
- **SQL:** SQLite, CTE, оконные функции, CASE-логика, подзапросы, агрегации
- **Python:** Pandas, Matplotlib, Seaborn, Glob, OS, Datetime
- **Концепции:** Бизнес-аналитика, сегментация данных, управленческая отчетность, ETL-пайплайны, контроль качества данных, проверка рыночных гипотез

## 📂 Структура проекта
'''
sber-sql-python-assessment/
├── Sber_SQL_Python_Assessment.ipynb # Единый ноутбук со всеми заданиями и визуализациями
├── data_for_test.txt # Исходные данные для Python ETL-задач
├── Тест_Python.docx # Оригинальные спецификации Python-заданий
├── Тест_SQL_логика_2510.docx # Оригинальные спецификации SQL-заданий
└── README.md
'''

## 💡 Ключевые бизнес-инсайты
- **Дисбаланс портфеля:** 72% клиентов находятся в сегментах «Низкая» и «Средняя» зарплата, но формируют непропорционально малую долю портфеля по сравнению с сегментами «Высокая» и «Premium».
- **Региональная стратегия:** Юго-Западный банк демонстрирует наибольший разброс зарплат (10k-150k руб.), что требует дифференцированной продуктовой стратегии.
- **Возможности кросс-продаж:** Клиенты Московского банка с зарплатой ~30k руб. показывают аномально высокий POS-оборот (35k руб.), что указывает на потенциал кредитных продуктов.
- **Рыночная динамика:** Рост GMV в марте 2022 был преимущественно обусловлен паническим спросом (60-70%), а не органическим расширением спроса.

## 🎯 Результат
Все технические задания успешно выполнены и защищены перед нанимающим руководителем. Проект демонстрирует способность транслировать абстрактные бизнес-запросы в структурированные решения на основе данных и практически применимые инсайты.
