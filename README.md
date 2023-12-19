---
title: Landmark Recognition
emoji: 😻
colorFrom: red
colorTo: yellow
sdk: streamlit
sdk_version: 1.29.0
app_file: main.py
pinned: false
---

# proj
Smart city gid
В приложенных файлах:
1. check_photo_model_retrain.py - файл для переобучения последнего слоя модели googlenet обученной на датасете IMAGENET1K_V1.
2. pikle_model.pkl  - сохранненная в файл переобученная модель из п.1. Обучена на подготовленном датасете
3. check_photo.py - запуск распознования фотографии моделью. Возращает определнную категорию и вероятность в долях.
4. test_check_photo.py - Запуск распознования фото на файлах из тестовой выборки (в папке Test_photo)
5. check_photo_model_init.py инициализация модели. Модель поднимается из файла pickle_model.pkl, категории полнимаются из файла cat.csv
6. wikipedia_api.py - поиск на Википедия. Принимается список для поиска, возвращается список с результатами поиска
7. picturedownloader - парсинг фото для обучения модели по bing, через crawler
