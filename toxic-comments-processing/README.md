# Модель классификации комментариев для интернет-магазина

## Описание проекта
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах.
Цель - построить инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Обучим модель классифицировать комментарии на позитивные и негативные. В распоряжении набор данных с разметкой о токсичности правок.

Значение метрики качества *F1* у модели должно быть не меньше 0.75. 

## Использованные техники и инструменты:
Numpy, scikit-learn, Python, Pandas, nltk, re, CatBoost, LightGBM, предобработка данных, NLP, стемминг, TF-IDF, кросс-валидация, обучение модели, анализ качества работы модели.