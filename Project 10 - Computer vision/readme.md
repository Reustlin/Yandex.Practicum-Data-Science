### Yandex.Practicum-Data-Science
# Определение возраста покупателей
## Задача:
Построить модель машинного обучения, определяющую примерный возраст человека по фотографии
## Описание:
Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.
## Используемые инструменты:
`pandas`, `numpy`, `matplotlib`, `seaborn`, `keras`, `tensorflow`, `Adam`
## Модели:
`ResNet50`
## Метрики
`MAE`
## Основные шаги и выводы:
* Анализ данных, подготовка
* Построение нейросети ResNet50: создание слоев, обучение и проверка на тестовой выборке
* Достижения целевой метрики MAE на тестовой выборки 6.02 при требуемой в 8
