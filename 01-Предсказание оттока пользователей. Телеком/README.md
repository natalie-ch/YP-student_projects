# Предсказание оттока пользователей. Телеком.
## Статус проекта.
Завершен.
## Задача. 
Спрогнозировать отток клиентов для телеком компании. 
Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
## Решение и вывод. 
Провели предобработку и анализ данных, полученных от оператора связи. 
В результате анализа были обнаружены заслуживающие внимания особенности клиентов, разорвавших отношения с телеком компанией. 
Также мы обучили несколько моделей с целью определить клиентов, которые потенциально могут покинуть оператора. 
Лучших показателей (roc_auc 0.912727 и 0.914147) достигли две модели CatBoost, при помощи которых оператор сможет выбрать, какому клиенту выслать промокод, а какой и так лоялен.
## Используемые библиотеки:
numpy, pandas, datetime, matplotlib, seaborn, sklearn, catboost, lightgbm
