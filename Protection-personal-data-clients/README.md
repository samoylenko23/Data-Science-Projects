# Прогнозирование временных рядов

**Описание задачи:** Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Необходимо добиться метрики RMSE < 48

**Используемые библиотеки:** 
1. Pandas
2. Statsmodels
3. tqdm
4. Seaborn
5. Matplotlib
6. scikit-learn
7. CatBoost
8. time
9. LightGBM

**Используемые алгоритмы и методы:**
* Декомпозиция веременных рядов: seasonal_decompose
* Машинное обучение. Нюансы моделей с учетом временного ряда
* Препроцецессинг: MinMaxScaler, StandardScaler, OrdinalEncoder
* Кросс-валидация c учетом временного ряда: TimeSeriesSplit, GridSearchCV, RandomizedSearchCV
* Градиентный бустинг: CatBoostRegressor
* RandomForestRegressor
* DummyRegressor
* SVR
* DecisionTreeRegressor
* LinearRegression, Ridge, Lasso
* Разработка Pipeline: Pipeline, ColumnTransformer
* EDA
* Визуализация данных
