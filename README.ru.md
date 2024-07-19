# TSOML - Машинное обучение окулограмм временных рядов ([ENG](https://github.com/termik88/VKR_ML/blob/main/README.md))
## Тема: "ИЗВЛЕЧЕНИЕ И КЛАССИФИКАЦИЯ ПРИЗНАКОВ ИЗ НАБОРА ДАННЫХ ОКУЛОГРАФИИ МЕТОДАМИ МАШИННОГО ОБУЧЕНИЯ"

### Автор

Колосов И.В.

### Научный руководитель

к.т.н. Долганов А.Ю.

### Ссылки

- [GitHub автора](https://github.com/termik88)

- [Профиль научного руководителя](https://urfu.ru/ru/about/personal-pages/Personal/person/anton.dolganov/)

- [Блокнот c исследованиями](https://github.com/termik88/VKR_ML/blob/main/vkr_research.ipynb)

- [Набор данных](https://figshare.com/collections/Screening_for_Dyslexia_Using_Eye_Tracking_During_Reading/3521379)

- [Отзыв научного руководителя](https://github.com/termik88/VKR_ML/blob/main/review%20-%20Scientific%20Supervisor.pdf)

- [Рецензия на ВКР от Кирилов Б.А. (МФТИ)](https://github.com/termik88/VKR_ML/blob/main/review%20-%20Expert.pdf)

- [Полный текст ВКР](https://github.com/termik88/VKR_ML/blob/main/text_vkr.pdf) 

### Описание
Целью данного **исследования** является анализ методов машинного
обучения для извлечения и классификации признаков из наборов данных
окулограмм для повышения точности диагностики дислексии.

Объектом исследования является обнаружение различных событий
движения глаз из данных окулограммы, включая прогрессивные и
регрессивные движения глаз, фиксации, саккады и типы полей зрения.

В исследовании изучается использование пороговых алгоритмов и
методов кластеризации на основе аномалий для идентификации этих событий.

В исследовании используется стратифицированная перекрестная
валидация и рекурсивный отбор признаков для выбора наиболее значимых
признаков для моделей машинного обучения, а также изучается вариативность
рекурсивного отбора признаков на основе точности предсказания и
вероятности извлечения признаков.

#### Библиотеки и технологии:
1.	Pandas
2.	NumPy
3.	Matplotlib
4.	Seaborn
5.	Plotly
6.	SciPy
7.	Statsmodels
8.	Scikit-learn
9.	HDSCAN
10.	XGBoost
#### Используемые модели:
1.	Логистическая регрессия (LogisticRegression, LogisticRegressionCV)
2.	Машина опорных векторов (SVC)
3.	Случайный лес классификатор (RandomForestClassifier)
4.	Классификатор градиентного бустинга (GradientBoostingClassifier)
5.	DBSCAN (Кластеризация по плотности с шумом)
6.	Локальный фактор аномалий (LOF)
7.	XGBoost (Экстремальный градиентный бустинг)


### Результаты

#### Средняя точность
0.9597701149425287

#### Интервал доверия (0.95) для точности
(0.91927 , 1.00000)

#### Отчет о классификации

|  | precision | recall | f1-score | support |
| --- | --- | --- | --- | --- |
| 0.0 | 1.00 | 0.90 | 0.95 | 20 |
| 1.0 | 0.89 | 1.00 | 0.94 | 17 |
| accuracy |  |  | 0.95 | 37 |
| macro avg | 0.95 | 0.95 | 0.95 | 37 |
| weighted avg | 0.95 | 0.95 | 0.95 | 37 |

### Ключевые слова

* Oculography
* Time Series
* Event Detection
* Eye Movements
* Machine Learning
* Fixations
* Saccades
* Interval Threshold
* Feature Extraction
* Classification
* Anomalies
* RFE
