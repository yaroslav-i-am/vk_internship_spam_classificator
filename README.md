# vk_internship_spam_classificator
---
## Условие:
Дан тренировочный датасет с текстами сообщений из мессенджера на английском языке. Для каждого из них проставлен флаг того, является ли сообщение СПАМом. 
Так же дан тестовый датасет с такими же текстами сообщений, но без флага. Необходимо проскорить модель и приложить результаты.

## Данные
* `text_type` - целевая переменная, флаг СПАМ/не СПАМ
* `text` - текст сообщения. 

## Задача: 
* Провести базовую аналитику по имеющимся данным
* Обучить модель по тексту сообщения определять, является ли ее содержимое СПАМом (ожидается, что будут опробованы несколько подходов, из которых аргументированно выбирается наилучший; можно использовать любую библиотеку или фреймворк)
* Целевой метрикой при оценке работы модели будет `ROC-AUC score`
* Произвести скоринг лучшей моделью тестовых данных, а результат записать в csv-файл в виде таблицы с колонками `score` и `text`
* Выложить код на `juруtег notebook` и результирующий файл со скорами модели на `https://github.com` отдельным проектом и поделиться ссылкой в поле для ответа. 

