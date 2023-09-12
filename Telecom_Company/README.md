# Прогноз оттока клиентов оператора услуг связи
[Jupyter Notebook]()

## Описание проекта
Необходимо подготовить прототип модели машинного обучения, которая должна прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.

## Навыки и инструменты
Python  
os  
pandas  
numpy  
seaborn  
matplotlib  
warnings  
sklearn.preprocessing.**LabelEncoder**  
sklearn.preprocessing.**StandardScaler**  
sklearn.preprocessing.**OneHotEncoder**  
scipy.stats.**chi2_contingency**  
sklearn.model_selection.**GridSearchCV**  
sklearn.model_selection.**train_test_split**  
sklearn.pipeline.**Pipeline**  
sklearn.compose.**make_column_transformer**  
sklearn.linear_model**LogisticRegression**  
sklearn.ensemble.**RandomForestClassifier**  
catboost.**CatBoostClassifier**  
sklearn.dummy.**DummyClassifier**  
sklearn.metrics import.**confusion_matrix**  
sklearn.metrics import.**roc_auc_score**  
sklearn.metrics import.**f1_score**  
sklearn.metrics import.**roc_curve**  
sklearn.metrics import.**accuracy_score**  
sklearn.metrics import.**make_scorer**

## Общий вывод
Проведено обучение нескольких моделей с контролем важных для заказчика критериев и метрик. Выбрана наиболее подходящая модель для запуска в эксплуатацию.
