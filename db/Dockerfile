



FROM mysql:5.7.25

ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="accounts"
ENV MYSQL_USER="admin"
ENV MYSQL_PASSWORD="admin123"

# تأكد من أن الملف db_backup.sql في نفس المجلد الذي يحتوي على Dockerfile
ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

