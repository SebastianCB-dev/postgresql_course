
1. Convertirse en usuario postgres 
sudo su - postgres

2. Crear ambiente
initdb --locale en_US.UTF-8 -D /var/lib/postgres/data

3. Conectarse
psql --username=freecodecamp dbname=postgres

4. Listar bases de datos
\l

5. crear base de datos
CREATE DATABASE database_name;

6. Conectar a base de datos
\c database_name

7. Ver tablas de una base de datos
\d

8. Ver descripcion de una tabla especifica en una base de datos
\d table_name;

9. Crear tabla
CREATE TABLE table_name();

10. Add column into a table
ALTER TABLE table_name ADD COLUMN column_name DATATYPE;

11. Remove column from a table
ALTER TABLE table_name DROP COLUMN column_name;







