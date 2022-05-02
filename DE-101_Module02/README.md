# Задание для модуля 2

## Устанавливаем PostgreSQL на локальный компьютер. Загрузка данных в БД. Запросы к БД

**Запросы для загрузки данных**

- [x] [2.3. table_rows.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/table_rows.sql) (orders)
- [x] [2.3. table_people.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/table_people.sql)
- [x] [2.3. table_returns.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/table_returns.sql)

**Делаем SQL запросы к БД**

- [x] [2.3. query.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/query.sql)

## Рисуем модель данных в SQLdbm для создания новой БД

**Концептуальная модель**

![Концептуальная модель](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/Conceptual_model.png)

**Логическая модель**

![Логическая модель](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/Logical%20model.png)

**Физическая модель**

![Физическая модель](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/Physical%20model.png)

## Создаём БД в AWS RDS и загружаем данные

- [x] Создаем учетную запись в AWS.
- [x] Используя сервис AWS RDS создаём БД PostgreSQL и настраиваем к ней доступ.
- [x] Подключаемся к новой БД через SQL клиент (DBeaver) и загружаем данные из модуля 2.3 (Superstore dataset):
  - [x] В staging (схема БД stg) — [stg.orders.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/stg.orders.sql)
  - [x] В Business Layer (схема БД dw) — [from_stg_to_dw.sql](https://github.com/niko-greb/datalearn/blob/main/DE-101_Module02/from_stg_to_dw.sql)

## Google Data Studio: подключение к БД в AWS RDS и создание дашборда

[Дашборд в Data Studio](ссылка)
