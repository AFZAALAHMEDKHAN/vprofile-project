FROM mysql:8.0.33
LABEL "Author"="Afzaal"

ENV MYSQL_ROOT_PASSWORD="Afzaal@21"
ENV MY_SQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql


#this is a change