FROM wordpress:latest

COPY wp-config.php /var/www/html/wp-config.php

#Stage 2 - MariaDB
FROM mariadb:latest

COPY my.cnf /etc/mysql/my.cnf
