FROM mysql:latest


ENV MYSQL_ROOT_PASSWORD ${MYSQL_ROOT_PASSWORD}
COPY ./data.sql /docker-entrypoint-initdb.d/data.sql