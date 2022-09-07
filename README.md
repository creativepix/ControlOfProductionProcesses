# ControlOfProductionProcesses

## Заметки по файлам:
model_action.cb - модель CatBoostClassifier для предсказания вышел человек или зашел

model_door.cb - модель CatBoostClassifier для предсказания двери, с которой связано действие

yolo_human_detect.pt - модель yolov5l, обученная для предсказания конкретно для этого датасета

frame_data.pkl - кэшированная информация о времени на кадрах ускоренных видео

people_data.pkl - кэшированна информация об аннотации людей на кадрах

{train1/train2/test}.avi - изначальные видео

{train1/train2/test}_fast.mp4 - ускоренные в 10 раз видео

train1_resized_fast.mp4 - ускоренное тренировочное видео, приведенное к общему размеру

{train1/train2/test}_fast_date.mp4 - видео с вырезанной датой из ускоренных видео

train.csv - данные для обучения предсказаний

test.csv - данные для предсказаний

## Доп. информация
Все файлы, с которыми производилась работа (будут доступны как минимум в течении 14 дней, поэтому советаю сохранить локально): https://drive.google.com/drive/folders/1MDRQwUxqW_6oeHWrTsJocgup1pTeY-yZ?usp=sharing

Скринкаст: https://youtu.be/7Hx_KxiPa9E
