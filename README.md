# Поиск аномалий

Запускалова Дарья 11-009
Кургускина Софья 11-004

## Видео с защитой проекта: 
https://drive.google.com/file/d/11OMlFRZHfrCG9e3uiVnRwHfNlKSf8Xpf/view?usp=sharing

## Google Collab:
https://colab.research.google.com/drive/1wxQp4jYmg7grIazaHmjSLqcJq51oPHMG?usp=sharing

## Датасет:
https://www.kaggle.com/datasets/zhonglifr/thyroid-disease-unsupervised-anomaly-detection

## Содержание
Проект состоит из Exploratory Data Analysis(EDA), в котором мы оцениваем распределение данных в текущем наборе данных, влияние атрибутов на целевую переменную.
Далее мы применяем алгоритмы поиска аномалий без учителя(представлены ниже).
- Isolation Forest
- COPOD(Copula-Based Outlier Detection)
- Elliptic Envelope
- One Class SVM
Как бонус в проекте представлен поиск аномалий с помощью CatBoostClassifier(набор данных уже размечен, в реальности такое бывает редко, но нам повезло)
## Результаты
На этом наборе данных качество моделей низкое, это можно обосновать плотностью распределния данных(аномалии находятся между нормальными значениями) и тем, что некоторые алгоритмы заточены на поиск скорее новизны, чем аномалий
