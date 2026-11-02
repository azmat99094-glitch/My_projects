# 📊 KION Subscription Base Analysis & Forecasting - English

## 📋 Overview
This project represents a comprehensive analysis of a video streaming service's subscription base (KION / On Media). Developed for a final-stage interview, the project involved evaluating cohort retention, identifying critical churn points, and building a 24-month forecast model. The analysis was successfully defended in person with the hiring manager.

## 🔍 Key Tasks Solved
1. **Data Quality Assessment**: Validated the dataset (435 records, 15 months). Confirmed no missing values, zero duplicates, and logical consistency (`Paying Users ≤ Active Users`).
2. **Cohort Analysis**: Calculated Retention Rates for cohorts from month 0 to 14. Identified critical churn periods (months 3-4 and 10-11).
3. **Trend Analysis**: Segmented the base lifecycle into a Growth Phase (months 0-6, +100k/mo) and a Decline Phase (months 7-14, peak at 785k users, current base at 197k).
4. **Forecasting & Scenario Planning**: Built a 24-month projection model based on historical cohort decay rates, incorporating optimistic/pessimistic scenarios and seasonality adjustments.

## 📝 Methodology Note
*The provided Excel file (`KION_Calculations.xlsx`) contains the final calculated values, structured tables, and pivot summaries for ease of review. The detailed calculation logic, forecasting assumptions (e.g., using a 3-month rolling window to avoid early-stage noise), and defensive arguments are fully documented in the PDF report and this README.*

## 🛠️ Tools
- **Microsoft Excel**: Advanced formulas, Pivot Tables, Cohort Matrix construction, Scenario forecasting.
- **Data Visualization**: Conditional formatting, trend charts.
- **Reporting**: PDF (Executive summary and strategic recommendations).

## 📂 Project Structure
```
kion-subscription-analysis/
├── data.csv # Raw anonymized subscription data
├── KION_Calculations.xlsx # Final calculated metrics and pivot tables
├── KION_Analysis_Report.pdf # Final presentation with insights and forecasts
└── README.md
```

## 💡 Key Business Insights
- **High Monetization, Low Engagement**: Paying user conversion grew to 98% (natural selection), but viewing activity dropped to 43%, indicating a large base of "sleeping" paid subscribers.
- **Forecast**: At the current decay rate, ~1.75M new subscriptions over 12 months will result in only ~415k active users by year-end.
- **Recommendations**: Focus on reactivating dormant payers, optimizing onboarding for cohorts 3-4 months old, and scaling the successful mechanics of Cohort #7 (highest 14-month retention at 14.64%).

---

# 📊 Анализ и прогнозирование подписочной базы KION - Русский

## 📋 Обзор
Проект представляет собой комплексный анализ подписочной базы видеосервиса (KION / On Media). Разработан для финального этапа отбора, работа успешно защищена лично перед нанимающим руководителем. Задачи включали оценку удержания когорт, выявление критических точек оттока и построение прогнозной модели на 24 месяца.

## 🔍 Решенные задачи
1. **Оценка качества данных**: Проверка датасета (435 записей, 15 месяцев). Подтверждено отсутствие пропусков, дубликатов и логическая корректность (`Платящие ≤ Активные`).
2. **Когортный анализ**: Расчет Retention Rate для когорт с 0 по 14 месяц. Выявлены критические точки оттока (3-4 и 10-11 месяцы).
3. **Анализ трендов**: Сегментация жизненного цикла базы на фазу роста (мес. 0-6, прирост ~100к/мес) и фазу спада (мес. 7-14, пик 785к, текущая база 197к).
4. **Прогнозирование**: Построена модель прогноза на 24 месяца на основе исторических темпов распада когорт, включая сценарный анализ (оптимистичный/пессимистичный) и учет сезонности.

## 📝 Примечание по методологии
*Предоставленный файл Excel (`KION_Calculations.xlsx`) содержит итоговые рассчитанные значения и сводные таблицы для удобства проверки. Подробная логика расчетов, допущения модели прогнозирования (например, использование 3-месячного окна для сглаживания шума первых месяцев) и аргументация подробно описаны в PDF-отчете и данном README.*

## 🛠️ Инструменты
- **Microsoft Excel**: Сложные формулы, сводные таблицы, построение когортных матриц, сценарное прогнозирование.
- **Визуализация данных**: Условное форматирование, трендовые графики.
- **Отчетность**: PDF (управленческое резюме и стратегические рекомендации).

## 📂 Структура проекта
```
kion-subscription-analysis/
├── data.csv # Исходные анонимизированные данные
├── KION_Calculations.xlsx # Итоговые метрики и сводные таблицы
├── KION_Analysis_Report.pdf # Финальная презентация с выводами и прогнозом
└── README.md
```

## 💡 Ключевые бизнес-инсайты
- **Высокая монетизация, низкая вовлеченность**: Конверсия в оплату выросла до 98% (естественный отбор), но доля смотрящих упала до 43%. Это указывает на большую базу "спящих" платных подписчиков.
- **Прогноз**: При текущих темпах оттока ~1.75 млн новых подключений за 12 месяцев дадут лишь ~415 тыс. активных пользователей к концу года.
- **Рекомендации**: Сфокусироваться на реанимации неактивных плательщиков, оптимизации онбординга для когорт 3-4 месяцев и масштабировании успешных практик когорты №7 (наивысший retention на 14 месяце — 14.64%).
