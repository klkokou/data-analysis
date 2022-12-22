# Поиск аномалий

Данные для проекта взяты с Kaggle https://www.kaggle.com/datasets/zhonglifr/thyroid-disease-unsupervised-anomaly-detection

Проект состоит из Exploratory Data Analysis(EDA), в котором мы оцениваем распределение данных в текущем наборе данных, влияние атрибутов на целевую переменную.
Далее мы применяем алгоритмы поиска аномалий без учителя(представлены ниже).
- Isolation Forest
- COPOD(Copula-Based Outlier Detection)
- Elliptic Envelope
- One Class SVM
Как бонус в проекте представлен поиск аномалий с помощью CatBoostClassifier(набор данных уже размечен, в реальности такое бывает редко, но нам повезло)
