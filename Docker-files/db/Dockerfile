FROM mysql:5.7.25
LABEL "Project"="Multi-tier"
LABEL "Author"="Bharath"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
