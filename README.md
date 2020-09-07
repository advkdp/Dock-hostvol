# Dock-hostvol
show databases
    -> ;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| somedatabase       |
| sys                |
+--------------------+
5 rows in set (0.01 sec)

mysql> use somedatabase
Database changed
mysql> show tables
    -> ;
Empty set (0.00 sec)

mysql> create table mytable (id INT);
Query OK, 0 rows affected (0.04 sec)

mysql> show tables;
+------------------------+
| Tables_in_somedatabase |
+------------------------+
| mytable                |
+------------------------+
1 row in set (0.00 sec)
