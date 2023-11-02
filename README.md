# Работа с признаками и построение моделей
* применение модели логистической регрессии и метода опорных векторов в задаче бинарной классификации (классификация по уровню доходов)
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ1.ipynb
* Функции потерь и оптимизация на датасете с ирисами - SGD, RMSProp, NADAM - сравнение метрик
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ2_2.ipynb
* Оценка точности модели, переобучение, регуляризация
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ3_1.ipynb
* Проблема качества данных (На примере Титаника)
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ4_2.ipynb
* EDA - Улучшить метрики RMSE, R2 модели линейной регрессии путем проведения EDA
  * Оставить лучшие признаки при помощи SelectKBest , f_regression и GridSearchCV
  * Удалить выбросы ( махалонобис)
  * Улучшение распределения признаков путем трансформации (логарифмированиеЮ, стандартизация)
  *  кластеризация и формирование нового признака claster
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ5.ipynb
* применение дерева решений в рамках задачи регрессии (данные о недвижимости Калифорнии) graphvis, plot_tree
    https://github.com/solobala/FEML23/blob/master/FEML23_DZ6.ipynb
* базовые ансамблевые методы (классификации наличия болезни сердца) -
DecisionTreeClassifier,RandomForestClassifier, BaggingClassifier, StackingClassifier,
бустинги - GradientBoostingClassifier, AdaBoostClassifier, LGBMClassifier, XGBClassifier, CatBoostClassifier
https://github.com/solobala/FEML23/blob/master/FEML23_DZ7_1.ipynb
* Поиск выбросов (классификация типов стекла).Проверка разных вариантов приведения признаков к нормальному распределению. Масштабирование данных методом скорректированного интервала. Поиск выбросов с помощью:
  * pyod - 30 различных алгоримов, проверим ECOD, IForest, OCSVM, LOF, KNN
  * Правило 3 сигм
  * Межквартильный размах
  * Удаление выбросов с использованием процентилей
  * Махаланобис
  * One Class SVM
  * DBSCAN
  * KNN
  * Isolation Forest
  https://github.com/solobala/FEML23/blob/master/FEML27_DZ8_3.ipynb
* Feature Selection c помощью SHAP, матрицы корреляции, Mutual Information, SelectKBest, LDA, PCA, NCA, SelectFromModel, feature_impotance, SequentialFeatureSelector.
  Поиск порога отсечения признаков с помощью VarianceThreshold
  https://github.com/solobala/FEML23/blob/master/FEML27_DZ9_1.ipynb
* Алгоритмы кластеризации KMeans, DBSCAN, HDBSCAN, AgglomerativeClustering. SSIM - потери от уменьшения к-ва цветов
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ10_2.ipynb
* Улучшение качества модели (классификации наличия болезни сердца) - GridSearchCV, RandomizedSearchCV
  https://github.com/solobala/FEML23/blob/master/FEML23_DZ11.ipynb
  
