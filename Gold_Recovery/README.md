# Исследование технологического процесса очистки золота
[Jupyter Notebook](gold_recovery.ipynb)

## Описание проекта
Необходимо построить модель машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Навыки и инструменты
Python  
pandas  
numpy  
seaborn  
matplotlib  
sklearn.tree.**DecisionTreeRegressor**  
sklearn.ensemble.**RandomForestRegressor**  
sklearn.linear_model.**LinearRegression**  
sklearn.dummy.**DummyRegressor**  
sklearn.model_selection.**cross_val_score**  
sklearn.model_selection.**GridSearchCV**  
sklearn.metrics.**mean_absolute_error**  
sklearn.metrics.**make_scorer**

## Общий вывод
Проведено обучение нескольких моделей с контролем качества их предсказаний. Выбрана наиболее подходящая модель для запуска в производство.
