CREATE USER 'justice'@'localhost' IDENTIFIED BY 'justice@1603';
GRANT ALL PRIVILEGES ON *.* TO 'justice'@'localhost' WITH GRANT OPTION;
CREATE USER 'justice'@'%' IDENTIFIED BY 'justice@1603';
GRANT ALL PRIVILEGES ON *.* TO 'justice'@'%' WITH GRANT OPTION;


python manage.py migrate
