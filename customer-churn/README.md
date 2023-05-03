
# Прогнозирование оттока клиентов

**Описание задачи:** Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Необходимо построить модель с предельно большим значением F1-меры. Преодолеть f1 метрику > 0.59. 

**Используемые библиотеки:** 
1. Pandas
2. phik
3. tqdm
4. Seaborn
5. Matplotlib
6. scikit-learn
7. CatBoost
8. imblearn
9. shap

**Используемые алгоритмы и методы:**
* EDA
* Визуализация данных
* Препроцецессинг: OneHotEncoder, MinMaxScaler, StandardScaler, OrdinalEncoder, KNNImputer
* Gradient Boosting: CatBoost
* LogisticRegression
* RandomForestClassifier
* DecisionTreeClassifier
* KneighborsClassifier
* DummyClassifier
* Написание своего класса для Pipeline: FunctionTransformer, ColumnTransformer, BaseEstimator, * TransformerMixin
* Pipeline
* SVC
* Борьба с дисбалансом: SMOTE, ADASYN, 
* Подбор параметров: GridSearchCV + StratifiedKFold, RandomizedSearchCV
* Интерпретация результатов: shap
