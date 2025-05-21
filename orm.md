<!-- communicating with the database -->
ORM-=>OBJECT RELATIONAL MAPPING <=> python object <=> database

turning objects  => to database records and viceversa

object <= establish database connection=>database

CRUD => create, read ,update, delete
create => CREATE TABLE table_name(colums)
       => INSERT INTO table_name(columns) (values)

read => SELECT * FROM table_name

update => UPDATE table_name SET name = "Pascal"
 WHERE id =2

 delete => DELETE FROM table_name WHERE ID = 1


 class => database tables

 Student => students
 Employee => employees


 class student:
    def __init__(self,name,age):
    self.name = name
    self.age = age