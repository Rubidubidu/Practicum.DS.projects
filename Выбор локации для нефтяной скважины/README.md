# Выбор локации для нефтяной скважины

## Цель

Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль, для определения места бурения новой скважины.

## Описание

Имеются данные с пробами нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.

Необходимо:
* Произвести анализ данных;
* Применить модель линейной регрессии для предсказания объёма сырья в месторождении по набору признаков в данных;
* Проанализировать возможную прибыль и риски техникой Bootstrap;
* Выбрать регион с наименьшей вероятностью убытков при заданном ограничении бютжета на бурение скважины.

## Используемые библиотеки

`Pandas`
`Numpy`
`Matplotlib`
`Scikit-learn`

## Результаты
* Был проведён исследовательский анализ данных, выявлен лучший регион и даны рекомендации заказчику;
* Подобрана модель машинного обучения для прогнозирования среднего запаса сырья;
* Расчитана прибыль и риски для каждого региона.
