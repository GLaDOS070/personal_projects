# Мониторинг дейтсвия лицензий у организаций по предоставлению услуг связи
## Задача
- Необходимо организовать мониторинг действия лицензий по москвоским организациям, которые осущесвляют следующие услуги:
    - Телематические услуги связи
    - Услуги связи по передаче данных, за исключением услуг связи по передаче данных для целей передачи голосовой информации
- Сбор данных происходит в 2 итерации по каждой услуги на отчетную дату
- На выходе формируется Excel файл, в котором есть 3 листа:
    1. данные по Телематическим услугам связи
    2. данные по Услугамам связи по передаче данных, за исключением услуг связи по передаче данных для целей передачи голосовой информации
    3. Объединение 2-таблиц в одну с удаление дубликатов (UNION)
## Что использовалось
- весь проект написан в Jupyter Notebook
### Основные библиотеки
- ```re```
- ```pandas```
- ```selenium```
<!-- # Пример результата -->
<!-- ![Пример выгрузки]() -->