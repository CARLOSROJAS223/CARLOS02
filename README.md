mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| Carlos0309$default |
| information_schema |
| performance_schema |
+--------------------+
3 rows in set (0.00 sec)

mysql> use Carlos0309$default;
Database changed
mysql> show tables;
+------------------------------+
| Tables_in_Carlos0309$default |
+------------------------------+
| USUARIOS                     |
| detalle_horario              |
| horario                      |
| plantilla_detalle_horario    |
+------------------------------+
4 rows in set (0.00 sec)

mysql> DESC USUARIOS;
+--------------+-------------+------+-----+---------+-------+
| Field        | Type        | Null | Key | Default | Extra |
+--------------+-------------+------+-----+---------+-------+
| nombre       | varchar(25) | YES  |     | NULL    |       |
| apellido     | varchar(25) | YES  |     | NULL    |       |
| departamento | varchar(25) | YES  |     | NULL    |       |
+--------------+-------------+------+-----+---------+-------+
3 rows in set (0.00 sec)

mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Dante', 'Dueñas','rh12);
    '> select * from USUARIOS;
    '> 

^C
mysql> select * from USUARIOS;
+--------+----------+--------------+
| nombre | apellido | departamento |
+--------+----------+--------------+
| Daniel | Gonzales | Rh12         |
+--------+----------+--------------+
1 row in set (0.00 sec)

mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Dante', 'Dueñas','rh12);
    '> select * from USUARIOS;
    '> 
    '> DESC USUARIOS;
    '> 

^C
mysql> select * from USUARIOS;
+--------+----------+--------------+
| nombre | apellido | departamento |
+--------+----------+--------------+
| Daniel | Gonzales | Rh12         |
+--------+----------+--------------+
1 row in set (0.00 sec)

mysql> 
mysql> 

^C
mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Dante', 'Dueñas','rh12);
    '> DESC USUARIOS;
    '> select * from USUARIOS;
    '> 

^C
mysql> show tables;
+------------------------------+
| Tables_in_Carlos0309$default |
+------------------------------+
| USUARIOS                     |
| detalle_horario              |
| horario                      |
| plantilla_detalle_horario    |
+------------------------------+
4 rows in set (0.00 sec)

mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Dante', 'Dueñas','rh12');
Query OK, 1 row affected (0.01 sec)

mysql> select * from USUARIOS;
+--------+----------+--------------+
| nombre | apellido | departamento |
+--------+----------+--------------+
| Daniel | Gonzales | Rh12         |
| Dante  | Dueñas   | rh12         |
+--------+----------+--------------+
2 rows in set (0.00 sec)

mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Cristiano', 'Ronaldo','rh07);
    '> select * from USUARIOS;
    '> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Dante', 'Dueñas','rh12);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'Dante', 'Dueñas','rh12)' at line 3
mysql> ^C

^C
mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Cristiano', 'Ronaldo','rh07');
Query OK, 1 row affected (0.00 sec)

mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Antoine', 'Griezzman','rh22');
Query OK, 1 row affected (0.01 sec)

mysql> select * from USUARIOS;
+-----------+-----------+--------------+
| nombre    | apellido  | departamento |
+-----------+-----------+--------------+
| Daniel    | Gonzales  | Rh12         |
| Dante     | Dueñas    | rh12         |
| Cristiano | Ronaldo   | rh07         |
| Antoine   | Griezzman | rh22         |
+-----------+-----------+--------------+
4 rows in set (0.00 sec)

mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Neymar', 'Aveiro','rh07');
Query OK, 1 row affected (0.00 sec)

mysql> select * from USUARIOS;
+-----------+-----------+--------------+
| nombre    | apellido  | departamento |
+-----------+-----------+--------------+
| Daniel    | Gonzales  | Rh12         |
| Dante     | Dueñas    | rh12         |
| Cristiano | Ronaldo   | rh07         |
| Antoine   | Griezzman | rh22         |
| Neymar    | Aveiro    | rh07         |
+-----------+-----------+--------------+
5 rows in set (0.00 sec)

mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Lionel', 'Messi'rh07');
    '>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Lionel', 'Messi','rh10');
    '>  

^C
mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Cristiano', 'Ronaldo','rh07);
    '> }
}
^C
mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Lionel', 'Messi','rh10');
Query OK, 1 row affected (0.01 sec)

mysql>  Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Guillermo', 'Ochoa','rh08);
    '> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Guillermo', 'Ochoa','rh08');
    '> 

^C
mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Guillermo', 'Ochoa','rh08');
Query OK, 1 row affected (0.00 sec)

mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Ronaldo', 'Nazario','rh09');
Query OK, 1 row affected (0.01 sec)

mysql> select * from USUARIOS;
+-----------+-----------+--------------+
| nombre    | apellido  | departamento |
+-----------+-----------+--------------+
| Daniel    | Gonzales  | Rh12         |
| Dante     | Dueñas    | rh12         |
| Cristiano | Ronaldo   | rh07         |
| Antoine   | Griezzman | rh22         |
| Neymar    | Aveiro    | rh07         |
| Lionel    | Messi     | rh10         |
| Guillermo | Ochoa     | rh08         |
| Ronaldo   | Nazario   | rh09         |
+-----------+-----------+--------------+
8 rows in set (0.00 sec)
mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Zinedine', 'Zidane','rh05');
Query OK, 1 row affected (0.01 sec)
mysql> Insert  into USUARIOS (nombre,apellido,departamento) values ( 'Lamine', 'Yamal','rh19');
Query OK, 1 row affected (0.01 sec)
mysql> select * from USUARIOS;
+-----------+-----------+--------------+
| nombre    | apellido  | departamento |
+-----------+-----------+--------------+
| Daniel    | Gonzales  | Rh12         |
| Dante     | Dueñas    | rh12         |
| Cristiano | Ronaldo   | rh07         |
| Antoine   | Griezzman | rh22         |
| Neymar    | Aveiro    | rh07         |
| Lionel    | Messi     | rh10         |
| Guillermo | Ochoa     | rh08         |
| Ronaldo   | Nazario   | rh09         |
| Zinedine  | Zidane    | rh05         |
| Lamine    | Yamal     | rh19         |
+-----------+-----------+--------------+
10 rows in set (0.00 sec)
mysql> mysql> show databases;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL serv
er version for the right syntax to use near 'mysql> show databases' at line 1
mysql> 
