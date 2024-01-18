ARG MYSQL_VERSION
FROM mysql:${MYSQL_VERSION}

COPY ./container/db/my.cnf /etc/mysql/conf.d/

RUN chmod 644 /etc/mysql/conf.d/my.cnf