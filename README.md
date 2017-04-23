# mipt-db
Материалы семинаров по курсу баз данных ФИВТ МФТИ

# [Курсовой проект](./project.md)

# Лабораторные работы
## Правила сдачи лаб
Каждая лабораторная работа сдаётся лично. Лабораторная считается сданной, если выполнены *все* задания и студент может ответить на вопросы семинариста. Лабораторную работа можно сдать: на семинаре, на котором она была выдана, на двух следующих за ним семинарах, либо на зачете в конце семестра. Сдача всех лабораторных работ является необходимым условием для получения положительной оценки за курс.

Лабы следует отправлять в виде текстового файла ("plain text", не в ворде и не в PDF). Этот файл должен быть валидным SQL: используйте однострочные комменты (два дефиса: `--`), чтобы указывать номера задач или любой другой текст, не являющийся частью запроса. Каждый запрос должен оканчиваться символом `;`. Имя файла с выполненными заданиями должно иметь формат `Lab<номер_лабы>_<номер_группы>_<Фамилия>.sql`. Пример: `Lab03_695_Kharitonov.sql`. 

1. [Простейшие `SELECT`-запросы.](https://github.com/kharvd/mipt-db/blob/master/labs/01.md)
1. [Соединение таблиц.](https://github.com/kharvd/mipt-db/blob/master/labs/02.md)
1. [Группировка и агрегатные функции. Оконные функции.](https://github.com/kharvd/mipt-db/blob/master/labs/03.md)

# Семинары
1. [Введение. Реляционная алгебра.](https://github.com/kharvd/mipt-db/blob/master/seminars/01.md)
2. [Реляционная алгебра (продолжение).](https://github.com/kharvd/mipt-db/blob/master/seminars/02.md)
3. [Исчисление кортежей.](https://github.com/kharvd/mipt-db/blob/master/seminars/03.md)
4. [Исчисление кортежей (продолжение). Язык SQL: оператор `SELECT`](https://github.com/kharvd/mipt-db/blob/master/seminars/04.md)

Также на семинарах обсуждались следующие темы:
1. Соединение таблиц, агрегатные функции (см. лабы).
1. Вставка, изменение и удаление данных ([[1]](https://www.postgresql.org/docs/current/static/sql-insert.html), [[2]](https://www.postgresql.org/docs/current/static/sql-update.html), [[3]](https://www.postgresql.org/docs/current/static/sql-delete.html)).
1. Создание таблиц ([[1]](https://www.postgresql.org/docs/current/static/tutorial-table.html)).
1. Первичные и внешние ключи ([[1]](https://en.wikipedia.org/wiki/Unique_key), [[2]](https://en.wikipedia.org/wiki/Foreign_key))
1. Ограничения ([[1]](https://www.postgresql.org/docs/current/static/ddl-constraints.html)).
1. Представления ([[1]](https://www.tutorialspoint.com/postgresql/postgresql_views.htm), [[2]](https://www.postgresql.org/docs/current/static/tutorial-views.html), [[3]](https://www.postgresql.org/docs/current/static/sql-createview.html)).
1. Элементы entity-relationship model ([[1]](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model)) и проектирования баз данных ([[1]](https://en.wikipedia.org/wiki/Database_design), [[2]](https://habrahabr.ru/post/193136/))
1. Работа с PostgreSQL из Python ([[1]](http://initd.org/psycopg/))
