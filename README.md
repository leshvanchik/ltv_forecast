# Прогноз LTV
Расчет производится на основе:
* когорт пользователей выдуманной match-3 игры, которые были привлечены через Facebook Ads
* установивших игру на промежутке 14 дней (18.09.2023 - 01.10.2023)
* валовой прибыли, которую они в принесли за первые 2 недели жизни в проекте
* функции логарифмической регрессии $y = a ln(x) + b$
### Когортный анализ
![Прибыль пользователей в течение первых 14 дней в проекте](https://github.com/leshvanchik/ltv_forecast/blob/76de51f0bdfeab43a8f6997c471e9115bdb378e6/table.png)
### Фактический среднекогортный LTV
![Фактический среднекогортный LTV](https://github.com/leshvanchik/ltv_forecast/blob/95b6645f11b6fa49c07befa44058348a8cf418d2/table_mini.png)
### Прогнозное значение LTV на 90-й день
![Прогнозное значение LTV](https://github.com/leshvanchik/ltv_forecast/blob/95b6645f11b6fa49c07befa44058348a8cf418d2/ltv_forecast.png)

Источник данных: devtodev.com
