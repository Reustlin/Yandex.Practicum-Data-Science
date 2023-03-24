# Yandex.Praсtiсum Data Science Projects
Репозиторий с проектами, созданными в рамках курса "Специалист Data Science" в Яндекс.Практикуме

### О курсе / About program

- Ссылка на курс: https://practicum.yandex.ru/data-scientist/

### Содержание: / Content:

  - [Анализ игровых платформ / Common project - *Project_01*]([Project 1 - Game platforms](https://github.com/Reustlin/Yandex.Practicum-Data-Science/tree/main/Project%201%20-%20Games%20platforms))
  - [Введение в машинное обучение / Introduction to machine learning  - *Project_02*](05_ml_intro_mobile_tariffs)
  - [Обучение с учителем / Supervised learning  - *Project_03*](06_customer_churn_forecasting)
  - [Машинное обучение в бизнесе / Machine learning in business  - *Project_04*](07_ml_for_business_oil_bores)
  - [Сборный проект / Common project  - *Project_05*](08_gold_recovery)
  - [Линейная алгебра / Linear algebra  - *Project_06*](09_linear_algebra)
  - [Численные методы (градиентный бустинг) / Numerical analysis (gradient boosting)  - *Project_17*](10_cars_cost_determining)
  - [Временные ряды / Time series  - *Project_8*](11_time_series_taxi_orders_forecasting)
  - [Машинное обучение для текстов / Machine learning for texts  - *Project_9*](12_nlp_toxic_texts)
  - [Извлечение данных / Data retrieval - *Project_10*](13_sql_and_airline_analytics)
  - [Компьютерное зрение / Computer vision  - *Project_11*](14_cv_img_age_recognition)
  - Рекомендации и обучение без учителя / Unsupervised learning
- [**Выпускной проект / Final project**  - *Project_final*](15_graduate_project_telecom_customer_churn)

## Проекты

|№| Название | Общая информация | Стек технологий |
|:---|:-------------------|:----------------------------------------------------------|:-----------:|
|12  |[(Дипломный проект) Прогнозирование оттока клиентов оператора связи](15_graduate_project_telecom_customer_churn/15_graduate_project_telecom_customer_churn.ipynb)|Необходимо научиться с высокой точностью прогнозировать отток клиентов телеком-оператора. Это позволит своевременно предложить промокоды и бонусы и сохранить клиента.|`catboost` `sklearn` `seaborn` `matplotlib` `plotly` `pandas` `numpy` `math`|
|11  |[(Computer vision) Определение возраста человека по фотографии](14_cv_img_age_recognition)|Чтобы сетевой супермаркет мог проверять добросовестность продавцов и делать целевые предложения своим покупателям, необходимо построить модель, которая по фотографии определит приблизительный возраст человека.|`Keras` `tensorflow` `Adam` `ResNet50` `ImageDataGenerator` `seaborn` `PIL` `pandas` `matplotlib` `plotly` `numpy`|
|10  |[(SQL) Аналитика в авиакомпании](13_sql_and_airline_analytics)|Необходимо получить из базы данных (PostgreSQL) данные авиакомпании о перелетах и проведении в этих городах фестивалей. После этого провести общий анализ данных и проверить связь фестивалей с перелетами.|`SQL` `PostgreSQL` `pandas` `matplotlib` `plotly` `mannwhitneyu`|
|9  |[(Обработка естественного языка) Определение токсичности комментариев](12_nlp_toxic_texts)|Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Для этого необходимо обучить модель классифицировать комментарии на позитивные и негативные|`BERT` `spacy` `SVC` `pymystem3` `re` `sklearn` `pandas` `numpy` `matplotlib` `plotly` `math`|
|8  |[(Временные ряды) Прогноз количества заказов такси на следующий час](11_time_series_taxi_orders_forecasting)|Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.|`TimeSeriesSplit` `catboost` `lightgbm` `statsmodels` `sklearn` `pandas` `numpy` `matplotlib` `plotly` `math` `time`|
|7  |[Определение стоимости автомобилей](10_cars_cost_determining)|Необходимо построить модель для определения стоимости автомобиля, с учетом ограничений обозначенных заказчиком|`catboost` `lightgbm` `sklearn` `pandas` `numpy` `matplotlib` `plotly` `math` `time`|
|6  |[Разработать метод преобразования данных для защиты персональной информации](09_linear_algebra)|Необходимо разработать метод преобразования данных, согласно которому будет сложно восстановить персональную информацию. Обосновать корректность его работы.|`sklearn` `pandas` `numpy` |
|5   |[Предсказание коэффициента восстановления золота из золотосодержащей руды](08_gold_recovery)|Нужно построить модель, которая предскажет коэффициент восстановления золота из золотосодержащей руды по данным с параметрами добычи и очистки.|`sklearn` `matplotlib` `plotly` `pandas` `numpy`|
|4   |[Выбор локации для нефтяной скважины](07_ml_for_business_oil_bores)|Нефтяной компании нужно решить, где бурить новую скважину. Для этого необходимо построить модель для определения региона, где добыча принесёт наибольшую прибыль.|`sklearn` `scipy` `matplotlib` `plotly` `pandas` `numpy`|
|3   |[Прогнозирование оттока клиентов банка](06_customer_churn_forecasting/06_customer_churn_forecasting.ipynb)|Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет|`sklearn` `pandas` `numpy` `matplotlib`|
|2   |[Рекомендация тарифов существующим клиентам](05_ml_intro_mobile_tariffs)|Необходимо построить систему, способную проанализировать поведение клиентов, давно не меняющих тарифные планы, и предложить пользователям новый тариф, отвечающий их предпочтениям.|`sklearn` `pandas`|
|1   |[Определение параметров коммерческой успешности компьютерных игр](04_game_dev_analytics)|Необходимо выявить определяющие успешность игры закономерности, чтобы сделать ставку на потенциально популярный продукт и спланировать рекламные кампании|`scipy` `matplotlib` `plotly` `pandas` `numpy` `math`|


## Контакты

- email: alex18_ivanov@mail.ru 
- telegram: @reustlin



