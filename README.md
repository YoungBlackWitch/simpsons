# Классификатор изображений симпсонов для kaggle

В рамках соревнования необходимо было научить модель классифицировать изображения из мультсериала за более чем 25 лет. Многие классы являются несбалансированными, поэтому проводилась аугментация и использовался  WeightedRandomSampler

## Модель

Использовались 2 кастомные простые модели

## Технологический стек:
- Pytorch
- Numpy
- Matplotlib
- Scikit-learn

## Во время обучения были получены следущие результаты: 
- ### График значений функции ошибки простой модели
<image src="simple_loss.png">

- ### График значений функции ошибки более сложной модели
<image src="loss.png">

###  Пример случайных предстказанных изображений 
<image src="predictions.png">

 Результат с соревнований - точность 95%