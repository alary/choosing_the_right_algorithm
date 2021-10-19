## Подбор оптимального алгоритма для сервиса по продажам подержанных автомобилей 

Задача проекта - определение стоимости подержанного автомобиля

Цель проекта - обучить несколько моделей определять стоимость автомобиля по его характеристикам 
и выбрать оптимальную модель по соотношению параметров: время обучения, скорость обучения и качество предсказаний.

Кодирование текстовых данных выполнено с помощью алгоритма Ordinal Encoder.

Обучение моделей выполнено с помощью `Решающего девера`, `Случайного леса` и `Градиентного бустинга (CatBoost, LightGBM)`
Для каждой модели выполнена оптимизация гиперпараметров с помощью метода `GridSearchCV`.    

___
### Исходные данные

* Характеристики автомобилей
* Стоимость автомобилей

___
### Используемые библиотеки
- pandas
- scikit-learn
- numpy
- matplotlib
- lightgbm
- catboost
- time
