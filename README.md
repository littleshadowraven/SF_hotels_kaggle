# SF_hotels_kaggle
This notebook was originally placed in the competition for SF https://www.kaggle.com/competitions/sf-booking

# Project 3. Competition on kaggle:. [SF-DST] Booking reviews

## Content
[1. Project description] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Project description)
[2. What case are we solving?] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#What case are we solving?)
[3. Brief information about the data] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Brief information about the data)
[4. Stages of work on the project] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Stages of work on the project)
[5. Results] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Results)
[6. Conclusions:] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Conclusions:)

### Project description
В этом проекте описана работа с датасетом, в котором содержатся сведения о 515 000 отзывов на отели Европы. Создана модель, которая предсказывает рейтинг отеля по данным сайта Booking на основе имеющихся в датасете данных. Модель улучшалась посредством разведывательного анализа данных.

:arrow_up: [к оглавнению] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Content)


### What case are we solving?
Представьте, что вы работаете дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

**Competition conditions:**
Данное соревнование является бессрочным и доступно для всех потоков.

    Срок выполнения соревнования устанавливается индивидуально в каждом потоке.

    Тестовая выборка представлена в LeaderBoard целиком.

    Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.


**Quality metric**
Метрика называется Mean Absolute Error (MAE) и показывает среднее отклонение предсказанных значений от фактических.

## Brief information about the data
Датасет имеет следующие признаки:
    hotel_address - адрес отеля
    review_date - дата, когда рецензент разместил соответствующий отзыв.
    average_score - средний балл отеля, рассчитанный на основе последнего комментария за последний год
    hotel_name - название отеля
    reviewer_nationality - национальность рецензента
    negative_review - отрицательный отзыв, который рецензент дал отелю.
    review_total_negative_word_counts - общее количество слов в отрицательном отзыв
    positive_review - положительный отзыв, который рецензент дал отелю
    review_total_positive_word_counts - общее количество слов в положительном отзыве
    reviewer_score - оценка, которую рецензент поставил отелю на основе своего опыта
    total_number_of_reviews_reviewer_has_given - количество отзывов, которые рецензенты дали в прошлом
    total_number_of_reviews - общее количество действительных отзывов об отеле
    tags - теги, которые рецензент дал отелю.
    days_since_review - продолжительность между датой проверки и датой очистки
    additional_number_of_scoring - есть также некоторые гости, которые просто поставили оценку сервису, а не оставили отзыв. Это число указывает, сколько там действительных оценок без проверки.
    lat - широта отеля
    lng - долгота отеля

:arrow_up:[к оглавлению] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Content)


### Stages of work on the project
    1. Загружаем данные и анализируем датасет
    2. Очистка и обработка датасета
        2.1 Работа с адресами отелей
        2.2 Работа с датами отзывов
        2.3 Работа с отзывами
    3. Нормализуем данные
    4. Обучение модели

:arrow_up:[к оглавлению] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Content)


### Results
Результатом является процент ошибок,  составляющий значение 12.32172. 

:arrow_up:[к оглавлению] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Content)


### Conclusions:
На момент загрузки этот результат занимает 3 место в лидерборде.
Что означает, что построенная модель неплохо предсказывает рейтинг отеля.

:arrow_up:[к оглавлению] (https://github.com/littleshadowraven/SF_hotels_kaggle/blob/main/README.md#Content)
