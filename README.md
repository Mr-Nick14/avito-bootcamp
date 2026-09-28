# Ориентация текстовых боксов Avito

`research.ipynb` проходит путь от простых моделей до геометрического метода. `research-real-data.ipynb` обучает этот метод на синтетике и IIIT5K, сравнивает результаты и создаёт `submission_iiit5k.csv`.

Для повторного запуска установите зависимости из `requirements.txt`. Тестовые изображения Avito положите в `test/images/`. [IIIT5K-Words](https://www.kaggle.com/datasets/prathmeshzade/iiit5k-words) положите в `external_data/iiit5k_words/` архивом или в распакованном виде.

В `artifacts/` лежат компактные признаки, таблицы метрик и обученная модель. Исходные изображения и локальное окружение в репозиторий не входят.
