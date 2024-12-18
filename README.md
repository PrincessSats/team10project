team10project
=============

Общие сведения
--------------

Данный проект является университетским заданием команды **Team10**. Цель проекта - создание модели **машинного обучения (ML)** для прогнозирования **индекса качества воздуха (ИКВ, AQI)** и чат-бота для **Telegram Messenger**.

* * * * *

Технологии
----------

-   **Язык программирования:** Python

-   **Используемые библиотеки:**

    -   `joblib`

    -   `pandas`

    -   `numpy`

    -   `sklearn`

    -   `geopy`

* * * * *

Структура
----------------

team10project/
│
├── data/                     # Данные для обучения и обработки
│   ├── extracted/            # Извлеченные данные
│   │   ├── df1_with_clusters.csv
│   │   ├── merged_by_date_full.csv
│   │   └── merged_by_date.csv
│   │
│   ├── processed/            # Обработанные данные
│   │   ├── cleaned_air_data_with_aqi.csv
│   │   ├── cleaned_weather_data.csv
│   │   ├── data_cleaned.csv
│   │   ├── merged_data copy.csv
│   │   ├── merged_data.csv
│   │   ├── test_data.csv
│   │   └── train_data.csv
│   │
│   └── raw/                  # Исходные данные
│       ├── air_data_with_aqi_and_coor.csv
│       ├── air_quality_with_aqi.csv
│       ├── cat1_moscow_objects.csv
│       └── moscow_weather_full.csv
│
├── model/                    # Обученная модель
│   └── new_aqi_model.pkl
│
├── notebooks/                # Jupyter Notebook файлы
│   ├── aqi_forecast.ipynb
│   ├── data_engineering.ipynb
│   ├── model_and_data_eng.ipynb
│   └── new_model_data_eng.ipynb
│
├── .gitignore                # Файл для исключения из Git
├── LICENSE                   # Лицензионное соглашение
└── README.md                 # Описание проекта

* * * * *

Как пользоваться
----------------

1.  **Напишите нашему Telegram чат-боту:**\
    👉 [@AQI_predicotr_bot](https://t.me/AQI_predicotr_bot)

2.  **Отправьте ваше геолокационное местоположение** через Telegram.

3.  **Получите прогноз:**\
    📊 В ответ вы получите **прогноз ИКВ на 7 дней**, если ваше местонахождение находится в **Москве**.

* * * * *

Лицензия
--------

Данный проект распространяется на условиях лицензии **MIT**.\
📄 Подробности отражены в файле `LICENSE`.

* * * * *

**Разработано командой Team10 ✨**