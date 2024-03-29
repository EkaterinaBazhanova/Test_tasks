# Описание

## 1. Файл test_task.ipynb
Вам необходимо построить базовый алгоритм распознавания текста из документов.

Основным документом будет являться паспорт РФ

Примеры 10 паспортов из открытых источников необходимо взять здесь:
https://disk.yandex.ru/d/kVdTaY8TuGvBkw

Вам необходимо:
1) подобрать открытые библиотеки по распознаванию документов и провести распознавания паспортов с указанной ссылки
2) подобрать API c помощью которых можно провести распознавание, провести распознавание
3) САМЫЙ ВАЖНЫЙ ПУНКТ - обучить собственный алгоритм (pytorch, tensorflow), которые распознает ФИО с паспорта (не пользуясь готовыми библиотеками OCR, но пользуясь открытыми данными по распознаванию текста)
Где взять датасет - GitHub - wlinna/russian-ocr: CNN-based Russian OCR (uni project)
Или сгенерировать самостоятельно из книг
4) составить ноутбук с результатами, выложить на гитхаб
5) прислать ссылку на решение и резюме в телеграм @frankshikhaliev
6) также заполнить форму
Стажировка datascience в Mindset (основная форма)

Обзор OCR для знакомства с темой можно посмотреть здесь
Распознавание паспорта

Срок выполнения - 10 дней

## 2. Файл solution.ipynb

Дано видео, необходимо:

взять каждый 15 кадр из него и согласно координатам
(xmin,ymin = 115, 210, xmax, ymax = 350, 445) вырезать картинку и сделать решейп на 116*116, сохранить данные изображения в папке;

в ручную рассортировать в две папки: первая -- где есть человек на рабочем месте, вторая -- где пустой стол;

мы получили базу из двух папок, обучить на ней нейронную сеть классификатор на keras и pytorch (чем меньше будет модель тем лучше).

Данные для задачи: https://disk.yandex.ru/d/zrh9-rYmgRgxPQ
