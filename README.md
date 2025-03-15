# Churn_Rate_Analysis

## Обзор
Этот проект посвящен анализу оттока клиентов с использованием методов машинного обучения. Цель состоит в том, чтобы выявить ключевые факторы, влияющие на удержание клиентов, и построить предсказательные модели для снижения уровня оттока.

## Функциональность
- Предобработка данных и исследовательский анализ (EDA)
- Генерация и отбор признаков
- Обучение и оценка моделей машинного обучения
- Выводы и рекомендации для бизнеса


## Датасет
Файл содержит данные о клиентах банка и их характеристиках, которые используются для предсказания оттока клиентов.
| Столбец           | Описание |
|-------------------|----------|
| **RowNumber**     | Номер строки в датасете. |
| **CustomerId**    | Уникальный идентификатор клиента. |
| **Surname**       | Фамилия клиента. |
| **CreditScore**   | Кредитный рейтинг клиента. |
| **Geography**     | Страна проживания клиента (France, Spain, Germany). |
| **Gender**        | Пол клиента (Male/Female). |
| **Age**           | Возраст клиента. |
| **Tenure**        | Стаж обслуживания в банке (в годах). |
| **Balance**       | Баланс на счете клиента. |
| **NumOfProducts** | Количество продуктов банка, которыми пользуется клиент. |
| **HasCrCard**     | Наличие кредитной карты (1 - есть, 0 - нет). |
| **IsActiveMember**| Является ли клиент активным пользователем (1 - да, 0 - нет). |
| **EstimatedSalary** | Оценочная зарплата клиента. |
| **Exited**        | Факт ухода клиента (1 - ушел, 0 - остался). |

## Используемые модели
- Логистическая регрессия
- Деревья решений
- Случайный лес
Производительность моделей оценивается с помощью метрики accuracy. 
