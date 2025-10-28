# Using a specific version of MySQL
FROM mysql:8.0.33

# Adding some tags
LABEL "Project"="Vprofile"
LABEL "Author"="AS"

# Credentials from application.properties
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

# Initializing a fresh instance, see Docker mysql docs
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql


