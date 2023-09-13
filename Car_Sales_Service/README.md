# Построение модели определения стоимости автомобиля
[Jupyter Notebook](car_sales_service.ipynb)

## Описание проекта
Необходимо построить модель машинного обучения, которая должна определять стоимость автомобиля по его описанию. Модель поможет сервису по продаже автомобилей с пробегом привлекать новых клиентов.

## Навыки и инструменты
Python  
pandas  
numpy  
seaborn  
matplotlib  
sklearn.model_selection.**train_test_split**  
sklearn.model_selection.**GridSearchCV**  
sklearn.metrics.**mean_squared_error**  
sklearn.preprocessing.**OrdinalEncoder**  
sklearn.preprocessing.**StandardScaler**  
lightgbm.**LGBMRegressor**  
sklearn.dummy.**DummyRegressor**  
sklearn.ensemble.**RandomForestRegressor**

## Общий вывод
Проведено обучение нескольких моделей с контролем важных для заказчика критериев и выбрана наиболее подходящая.
