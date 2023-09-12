# Прогнозирование количества заказов такси на следующий час
[Jupyter Notebook]()

## Описание проекта
Необходимо построить модель машинного обучения, которая должна спрогнозировать количество заказов такси на следующий час. Модель поможет привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты
Python  
pandas  
numpy  
seaborn  
matplotlib  
statsmodels.tsa.seasonal.**seasonal_decompose**  
sklearn.metrics.**mean_squared_error**  
sklearn.model_selection.**train_test_split**  
sklearn.model_selection.**cross_val_score**  
sklearn.model_selection.**TimeSeriesSplit**  
sklearn.model_selection.**GridSearchCV**  
sklearn.linear_model.**LinearRegression**  
sklearn.ensemble.**RandomForestRegressor**  
sklearn.dummy.**DummyRegressor**  
catboost.**CatBoostRegressor**  

## Общий вывод
Проведено обучение нескольких моделей с контролем качества их предсказаний. Выбрана наиболее подходящая модель для запуска в производство.
