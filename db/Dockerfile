FROM mysql:latest

ARG MYSQL_ROOT_PASSWORD=nimda
ARG MYSQL_DATABASE=example_db
ARG MYSQL_USER=example_db_user
ARG MYSQL_PASSWORD=example_db_pass


VOLUME /var/lib/mysql
COPY mysql-init.sql /docker-entrypoint-initdb.d

EXPOSE 3306

CMD ["mysqld"]
