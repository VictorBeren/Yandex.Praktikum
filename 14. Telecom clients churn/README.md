# Прогноз оттока клиентов телекоммуникационной компании
---
#### Задача
Спрогнозировать вероятность расторжения договора клиентов с компанией в ближайшее время. Добиться значения целевой метрики (F1-мера) не менее 0.85.
#### Описание проекта
Проведена предобработка данных, добавлены новые признаки. Исследованы различия среди ушедших и оставшихся клиентов. Проверена гипотеза о том, что ушедшие клиенты приносили больше прибыли компании.
Построена модель для предсказания вероятности ближайшего ухода клиента компании (AUC-ROC=0.95, Accuracy=0.9).
Проведён сравнительный анализ моделей: логистической регрессии, случайного леса и CatBoost (градиентный бустинг).
#### Использованные библиотеки
pandas, numpy, scipy, sklearn, catboost, matplotlib, timeit
#### Описание данных
Предоставлены персональные данные о некоторых клиентах, информацию об их тарифах и договорах.