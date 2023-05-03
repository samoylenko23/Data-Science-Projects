
# Прогнозирование рыночной стоимости автомобиля

**Описание задачи:** Сервис по продаже автомобилей  разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. 
Необходимо построить модель, которая умеет её определять. В нашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.
Критерии, которые важны заказчику:
1.  качество предсказания;
2.  время обучения модели;
3.  время предсказания модели.

**Используемые библиотеки:** 
1. Pandas
2. LightGBM
3. tqdm
4. Scipy
5. Matplotlib
6. Scikit-learn
7. CatBoost
8. time
9. phik

**Используемые алгоритмы и методы:**
* Машинное обучение 
* EDA
* Визуализация данных
* Препроцецессинг: OneHotEncoder, MinMaxScaler, StandardScaler, OrdinalEncoder, SimpleImputer
* Кросс-валидация: StratifiedKFold, GridSearchCV, RandomizedSearchCV
* Градиентный бустинг: CatBoostRegressor, LGBMRegressor
* RandomForestRegressor
* DummyRegressor
* SVR
* LinearRegression, Ridge, Lasso
* Разработка Pipeline: Pipeline, ColumnTransformer
