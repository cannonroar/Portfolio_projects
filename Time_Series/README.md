# Создание модели предсказания заказов такси


## Задача

На основе исторических данных о заказах такси в аэропортах создать модель прогнозирования количества заказов на ближайший час для привлечения большего числа водителей в период пиковой нагрузки. Поставлено условие что метрика *RMSE* модели должна быть меньше 48.

## Стек

Python, библиотеки:

- *pandas,*
- *numpy,*
- *sklearn,*
- *LGBM,*
- *statsmodels,*
- *seaborn*

## Вывод

В ходе выполнения проекта были проведены следующие этапы:
1) Исходные данные были подготовлены с проведением ресэмплинга с шагом в 1 час;
2) Проведен анализ предоставленых данных, изучение скользящего среднего, выявлены закономерности в количестве заказов в течении недели и в течении суток;
3) Обучено несколько моделей, на валидационных данных подобраны наилучшие гиперпараметры для каждой из них;
4) Проведена проверка моделей на тестовых данных, определена модель наиболее точно предсказывающая количество заказов. *RMSE* наилучшей модели получено 39.5, что удовлетворяет поставленному условию.

## Статус проекта
Завершен.
