FROM mysql:5.7.25
LABEL "Project"="vprofileapp"
LABEL "Author"="Alexander Kozyr"
ENV MYSQL_ROOT_PASSWORD="Str0ngP4sswD"
ENV MYSQL_DATABASE="accounts"
ENV MYSQL_USER="vp_admin"
ENV MYSQL_PASSWORD="S3cr3tP4ss"
COPY db_backup.sql /docker-entrypoint-initdb.d
EXPOSE 3306
CMD ["mysqld"]