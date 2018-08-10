#创建数据库

`create databse justice;
CREATE USER 'justice'@'localhost' IDENTIFIED BY 'justice';
GRANT ALL PRIVILEGES ON *.* TO 'justice'@'localhost' WITH GRANT OPTION;
CREATE USER 'justice'@'%' IDENTIFIED BY 'justice';
GRANT ALL PRIVILEGES ON *.* TO 'justice'@'%' WITH GRANT OPTION;`


#表初始化
python manage.py migrate
