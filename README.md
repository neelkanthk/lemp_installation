# lemp_installation
A series of steps to follow for installing LEMP stack on Linux

1. sudo apt update
2. sudo apt install nginx
3. sudo apt install mysql-server
4. sudo apt install php-fpm php-mysql php-mbstring php-dom php-zip

5. sudo mysql
mysql> CREATE USER 'example_user'@'%' IDENTIFIED WITH mysql_native_password BY 'password';
mysql> GRANT ALL ON example_database.* TO 'example_user'@'%';
mysql> exit
