# project_regress
Project from GeekBrains course. Goal: predict house value

Ссылка на ноутбук в Colaboratory - https://drive.google.com/file/d/1y4CgZAPFg4WQzvvc3SMyAQV7FK0Byv4Z/view?usp=sharing

Курсовой проект для курса "Python для Data Science"

Материалы к проекту (файлы):
train.csv
test.csv

Задание:
Используя данные из train.csv, построить
модель для предсказания цен на недвижимость (квартиры).
С помощью полученной модели предсказать
цены для квартир из файла test.csv.

Целевая переменная:
Price

Основная метрика:
R2 - коэффициент детерминации (sklearn.metrics.r2_score)

Вспомогательная метрика:
MSE - средняя квадратичная ошибка (sklearn.metrics.mean_squared_error)
