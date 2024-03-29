### Yandex.Practicum-Data-Science
# Определение конечной температуры металла в ковше
## Описание проекта
Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. 

## Цель проекта

Построить модель, которая предскажет температуру стали.

## Признаки
Данные состоят из файлов, полученных из разных источников:

- `data_arc_new.csv` — данные об электродах;
- `data_bulk_new.csv` — данные о подаче сыпучих материалов (объём);
- `data_bulk_time_new.csv` *—* данные о подаче сыпучих материалов (время);
- `data_gas_new.csv` — данные о продувке сплава газом;
- `data_temp_new.csv` — результаты измерения температуры;
- `data_wire_new.csv` — данные о проволочных материалах (объём);
- `data_wire_time_new.csv` — данные о проволочных материалах (время).

Во всех файлах столбец `key` содержит номер партии. В файлах может быть несколько строк с одинаковым значением `key`: они соответствуют разным итерациям обработки.
## Целевой признак

* Конечная температура

### Используемые инструменты
`catboost` `lightgbm` `sklearn` `pandas` `numpy` `matplotlib` `plotly` `math` `time` `xgboost` `pipeline` `seaborn`

### Модели
`CatBoostRegressor` `LGBMRegressor` `DecisionTreeRegressor` `RandomForestRegressor` 

### Дополнительно
`OneHotEncoder` `OrdinalEncoder` `GridSearchCV` `make_scorer`

### Метрики
`mean_squared_error`

### План работы:

##### Провести анализ данных 

* Здесь планируется работа с пропусками, анализ выборосов. 
* Провека значений на адекватность, т.е. сооветствуют ли они процессу. 
* Инструменты: info, describe, гистограмма, ящик с усами, корреляция.
* Оформляем вопросы по бизнесу для заказчика
* Оформляем предварительные выводы по разделу

#####  Чистим данные, подготавливаем их

* Чистим данные
* Создаем итоговую таблицу данных, проверяем данные на корреляцию, 
* Сотовим к работе с моделью: преобразовываем/создаем новые признаки
* Оформляем предварительные выводы по разделу

#####  Обучить модель

* Делим на трейн и тест выборку, используем различные модели, например, линейная регрессия, лес, котбуст и лайтгбм. 
* Для подбора параметров используем гридсерч.
* Выбираем наилучшую модель
* Проверяем на тестовой выборке
* Оцениваем важность признаков после обучения
* Сравниваем с дамми моделью.
* Оформляем предварительные выводы по разделу

##### Подготавливаем отчет

* Делаем общий вывод о проделанной работе, ещё раз обозначаем какие пробелемы возникли в данных, 
* Добавляем итоговые рекомендации в рамках всего проекта. 
* Формулируем наши результаты относительно требуемой итоговой метрики, добавляем комментарии, как ещё могли бы её улучшить/сделать стабильнее работу модели
