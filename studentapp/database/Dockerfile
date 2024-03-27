FROM mysql:latest

LABEL database="studentapp"

ENV database="studentapp"

COPY init-db.sql /docker-entrypoint-initdb.d/

CMD ["mysqld"]

