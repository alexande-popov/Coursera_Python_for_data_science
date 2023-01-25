# Coursera_Python_for_data_science

Упражнения из курса "Python для анализа данных".

https://www.coursera.org/learn/python-for-data-science/home/info

##  [Week 1](week_1). Математика и Python для анализа данных.
* Знакомство с библиотекой `numpy`: [`matrices.ipynb`](week_1/matrices.ipynb).
* Знакомство с библиотекой `scipy`: [`matrices.ipynb`](week_1/matrices.ipynb).
* Знакомство с библиотекой `pandas`.
* Объект `pandas.Series`: [`Series.ipynb`](week_1/Series.ipynb).
* Объект `pandas.DataFrame`: [`DataFrame.ipynb`](week_1/DataFrame.ipynb).
* Группировка данных: [`Tinkoff.ipynb`](week_1/Tinkoff.ipynb).
* Работа с несколькими таблицами.
* Преобразование признаков.

## [Week 2](week_2). Визуализация данных и статистика.
* Визуализация с `matplotlib`.
* Расширенная визуализация с `matplotlib`.
* Визуализация с `pandas`.
* Интерактивная визуализация с `plotly`.
* Статистика в `scipy`: [`Stat_distributions.ipynb`](/week_2/Stat_distributions.ipynb).

## [Week 3](week_3). Обучение с учителем.
* Применение линейных моделей `sklearn.linear_model`:
    * (линейная) регрессия:
        * `LinearRegression`: [regression](/week_3/linear_models_regression.ipynb);
        * с регуляризацией L2, L1, L1+L2 (`Ridge`, `Lasso`, `ElasticNet`): [task-3.1](/week_3/task-3.1.ipynb), [task-3.2.1](/week_3/task-3.2.1-Regularization-Ridge-Lasso.ipynb)
    * логистическая регрессия (задача классификацииклассификации) `LogisticRegression`: [classification](/week_3/linear_models_classification.ipynb), [cross-validation](/week_3/linear_models_cross_validation.ipynb)
* Стандартизация данных `sklearn.preprocessing.StandardScaler`: [task-3.1](/week_3/task-3.1.ipynb)
* Разбиение на тренировочную и тестовую выборки `sklearn.model_selection`:
    * `train_test_split`: [task-3.1](/week_3/task-3.1.ipynb), [task-3.2.2](/week_3/test_5_task-3.2.2-Metrics.ipynb)
    * Кросс-валидация k-fold  `KFold`: [KFold](/week_3/linear_models_cross_validation.ipynb), [StratifiedKFold](/week_3/test_5_task-3.2.2-Metrics.ipynb)
* Метрики качетсва:
    * классификация: [бинарная](/week_3/linear_models_classification.ipynb), [бинарная, cross_val_score](/week_3/test_5_task-3.2.2-Metrics.ipynb)
    * регрессия: [task-3.1](/week_3/task-3.1.ipynb)
    
##  [Week 4](/week_4_Unsupervised_Learning_Methods/). Обучение без учителя.
* Методы кластеризации:
    * Метод k-средних: [`KMeans()`](/week_4_Unsupervised_Learning_Methods/k_means_clustering.ipynb)
    * Иерархическая агломеративная: [dendrogram](/week_4_Unsupervised_Learning_Methods/agglomerative_hierarchical_clustering.ipynb)
