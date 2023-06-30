FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=m1y591
ENV MYSQL_DATABASE=blogdata

COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

VOLUME /var/lib/mysql
