### Yandex.Practicum-Data-Science
# Определение стоимости автомобилей
## Описание проекта
Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Для этого необходимо построить модель для определения этой стоимости. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

## Заказчику важны:

* качество предсказания;
* скорость предсказания;
* время обучения.
* Описание данных
## Признаки

* DateCrawled — дата скачивания анкеты из базы
* VehicleType — тип автомобильного кузова
* RegistrationYear — год регистрации автомобиля
* Gearbox — тип коробки передач
* Power — мощность (л. с.)
* Model — модель автомобиля
* Kilometer — пробег (км)
* RegistrationMonth — месяц регистрации автомобиля
* FuelType — тип топлива
* Brand — марка автомобиля
* NotRepaired — была машина в ремонте или нет
* DateCreated — дата создания анкеты
* NumberOfPictures — количество фотографий автомобиля
* PostalCode — почтовый индекс владельца анкеты (пользователя)
* LastSeen — дата последней активности пользователя
## Целевой признак

* Price — цена (евро)
# Используемые инструменты
`catboost` `lightgbm` `sklearn` `pandas` `numpy` `matplotlib` `plotly` `math` `time` `xgboost`

# Модели
`CatBoostRegressor` `LGBMRegressor` `DecisionTreeRegressor` `RandomForestRegressor` `LinearRegression` `DummyRegressor` `XGBoostRegressor`

# Дополнительно
`OneHotEncoder` `OrdinalEncoder` `GridSearchCV` `make_scorer`

# Метрики
`mean_squared_error`
