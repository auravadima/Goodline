# Третий набор требований  

1. Создать файл Roadmap3.md  (20 min)
     1. Описать ход работы над третьим набором требований
2. Добавить логгирование неверно введённых данных R3.1 (80 min)
     1. Подключить библиотеку log4j2 (10 min)
         1. Добавить в Main логиирование в случаях, когда данные неверны (15 min)
         2. Создать файл настроек log4j2.xml для вывода логов в файл aaa.log (55 min)
             1. Какой синтаксис? (15 min)
             2. Какие параметры нужны? (15 min)
             3. Прочитать документацию (15 min)
             4. Найти пример настроек (10 min)
3. Хранить данные во встраиваемой СУБД R3.3 (75 min)
     1. Подключить библиотеку H2 (10 min)
     2. Создать три таблицы (USERS, AUTH, ACC) (20 min)
         1. Узнать синтаксис SQL запросов
     3. Вынести все SQL запросы в отдельные файлы (10 min)
     4. Создать класс для работы с БД (20 min)
         1. Написать методы для подключения к БД и получения из неё данных
         5. Получать данные о пользователях из базы данных (15 min)
4. Инициализировать файл aaa.db если он отсутствует и инициализировать схему БД R3.5 (20 min)
     1. Подключить библиотеку flyway (10 min)
     2. Добавить метод для инициализации схемы БД (10 min)
5. Заполнить таблицы БД текстовыми данными R3.6 (10 min)
     1. С помощью библиотеки flyway добавить миграцию БД из файлов *.sql созданных на шаге 3.3 (10 min)
6.  Исключить возможность SQLI R3.7 R3.8 (60 min)
     1. Узнать способы SQLI (20 min)
     2. Узнать способы защиты от SQLI (20 min)
     3. Узнать о PreparedStatement (10 min)
     4. Применить один из способов (10 min)

| Пункт | Предполагаемое время(mins) | Реальное время(mins) |
| --- | --- | --- |
|  1  |  20 |  15 |
|  2  |  80 | 100 |
|  3  |  75 |  60 |
|  4  |  20 |  15 |
|  5  |  10 |  10 |
|  6  |  60 |  15 |
| Sum | 265 | 215 |