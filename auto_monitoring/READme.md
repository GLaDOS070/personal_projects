# Мониторинг цен с Яндекс Маркета
## Задача
- Необходимо организовать мониторинг цен, которые парсятся с Яндекс Маркета
- Выгрузки ежеденевно (по будням) приходят в формате Excel
- Выгрузки необходимо добавлять в Google Sheets ("хранилище данных")
- Необходимо парсить данные по курсу доллара ЦБ для расчета цен в долларах
## Что использовалось
- весь проект написан в Jupyter Notebook, а визуализация в Yandex DataLense
### Основные библиотеки
- ```requests```
- ```pandas```
- ```gspread```
- ```oauth2client```
### Демо-версию дашборда можно посмотреть
[здесь](https://datalens.yandex.ru/8219beu2povoy-ezhenedelnyy-monitoring-cen)
# Пример результата
## Пример данных
![Пример данных](https://github.com/GLaDOS070/personal_projects/blob/main/auto_monitoring/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.png)
## Пример Дашборда
![Пример Дашборда](https://github.com/GLaDOS070/personal_projects/blob/main/auto_monitoring/%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0.png)
