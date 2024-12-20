# Описание проекта  

HR-аналитики компании помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают, как избежать финансовых потерь и оттока сотрудников. Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании.

**В результате работы над проектом:**
- была построена модель, предсказывающая уровень удовлетворённости сотрудника на основе данных заказчика (*Задача 1*). При её решении на основе созданной метрики `SMAPE` c использованием пайплайна была отобрана лучшая модель (`DecisionTreeRegressor`), определены её гиперпараметры;
- была построена модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании (*Задача 2*). При её решении на основе метрики `ROC-AUC` c использованием пайплайна была отобрана лучшая модель (`DecisionTreeClassifier`), и определены её гиперпараметры.

**Навыки и инструменты:**  
- `python`
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn.linear_model.LinearRegression, LogisticRegression`
- `sklearn.tree.DecisionTreeRegressor, DecisionTreeClassifier`
- `sklearn.pipeline.Pipeline`

К **предложениям для бизнеса** можно отнести:

- необходимость следить за удовлетворенностью работой своих сотрудников, 
- ускорить систему повышения в должности с junior в разряд middle,
- следить за загруженностью работой сотрудников, активнее вовлекать их в рабочий процесс,
- не забывать повышать зарплату, поощрять активность / инициативу.
