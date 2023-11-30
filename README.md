## Обработка данных:
Проведена обработка признаков тренировочного и тестового наборов данных, включая подсчет основных статистик, заполнение пропущенных значений, удаление дубликатов, приведение единиц измерения к правильному типу данных и преобразование некоторых признаков.

## Анализ данных:
Построены попарные распределения числовых признаков, описаны связи между предикторами и целевой переменной, а также выявлены корреляции признаков с помощью heatmap и диаграммы рассеяния.

## Обучение:
Обучены модели на вещественных признаках, такие как Linear Regression, Lasso и ElasticNet. Применены OneHotEncoder и обучена модель Ridge с использованием GridSearchCV для категориальных признаков. Произведено Feature Engineering, включая проверку на выбросы, создание новых признаков и генерацию полиномиальных признаков.

## Результаты:
Наибольший буст в качестве модели был достигнут за счет двух факторов: создания нового признака 'model' и включения полиномиальных признаков. Эти изменения существенно улучшили качество моделирования, поднимая его с начальных 60% до конечных 93%.

## Не получилось:
Был уверен, что добавление категориального признака "комплектация" сильно повысит качество предсказания. Однако метрика совсем не изменилась
