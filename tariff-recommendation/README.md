# Рекомендация тарифов

**Описание задачи:** Оператор мобильной связи  выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Необходимо получить accuracy > 0.75.

**Используемые библиотеки:** 
1. Pandas
2. Numpy
3. phik
4. Seaborn
5. Matplotlib
6. scikit-learn
7. CatBoost
8. imblearn
9. SHAP

**Используемые алгоритмы и методы:**
* EDA
* Shap – интерпретация результатов моделей
* Борьба с дисбалансмо классов - imblearn : under_sampling и over_sampling
* Визуализация
* Предобработка данных: MinMaxScaler
* Применение Pipeline: Pipeline
* Градиентный бустинг: catboost
* DecisionTreeClassifier
* RandomForestClassifier
* KneighborsClassifier
* LogisticRegression
* Кросс-валидация и подбор параметров: GridSearchCV, StratifiedKFold, cross_val_score

