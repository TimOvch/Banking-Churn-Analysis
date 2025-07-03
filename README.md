# Banking Churn Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-yellowgreen)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-blueviolet)

Анализ оттока клиентов банка с использованием методов Data Science и Machine Learning.

## 📌 О проекте

Этот проект направлен на изучение факторов, влияющих на отток клиентов банка (churn rate), и создание интерактивного дашборда для взаимодействия с данными.  

**Основные задачи:**  
- Разведочный анализ данных (EDA)  
- Визуализация ключевых метрик и поиск инсайдов 
- Построение ML-модели для изучения важности признаков
- Создание интерактивного дашборда в Tableau
- Рекомендации по снижению churn rate  

## 📂 Данные

- Источник: [Bank Customer Churn Prediction](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction/data)
- Объем: 10 000 строк, 13 столбцов.
- Файл с данными: `data/raw/Churn_Modeling.csv`  

Используемый датасет содержит информацию о клиентах банка, включая:  
1. CustomerId - уникальная числовая последовательность характеризующая отдельного клиента
2. Surname - фамилия клиента
3. CreditScore - числовой показатель, показывающий кредитоспособность человека
4. Geography - местоположение клиента
5. Gender - пол клиента
6. Age - возвраст клиента
7. Tenure - срок пользования услугами банка
8. Balance - баланс клиента
9. NumOfProduct - количество активных продуктов банка у клиента
10. HasCrCard - имеет ли клиент кредитные карты
11. IsActiveMember - является ли клиент активным пользователем
12. EstimatedSalary - предполагаемая зарплата клиента
13. Exited - Отказался ли клиент от услуг банка


## ⚙️ Инструменты
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy, LightGBM).
- Jupyter Notebook.
- Tableau.

## 📤 Результаты

С результатами анализа можно ознакомиться в презентации `reports/Banking Churn Analysis Report.pptx.pdf`
