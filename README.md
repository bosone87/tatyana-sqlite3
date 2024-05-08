# Создание схемы БД в sqlite3

**Устанавливаем sqlite3 в операционной системе Debian 12**
```bash
sudo apt-get install sqlite3
```

**Создаём базу данных learning.db**
```bash
sqlite3 learning.bd
```

**Создаём таблицы со связями между собой**

<p align="center">
    <img width="1200 height="600" src="sqllite3_create_db_table.png">
</p>

```
- Таблица teacher (учитель) связанна столбцом teach (учить) со столбцом id таблицы student (ученик)
- Таблица shcool (школа) связанна столбцом located (находиться) со столбцом id таблицы student (ученик)
- Таблица class (класс) связанна столбцом study (учиться) со столбцом id таблицы student (ученик)
- Таблица student (ученик)
```

[Для ответа на возможные вопросы, рекомндую ознакомиться со статьёй -](https://metanit.com/sql/sqlite/2.4.php)