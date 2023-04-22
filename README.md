Docker compose for lab PgSQL replica

Related links:

https://hub.docker.com/_/postgres

https://hub.docker.com/r/bitnami/postgresql#configuration

Prepare:

NOTE: As this is a non-root container, the mounted files and directories must have the proper permissions for the UID 1001 

mkdir -v pg-{main,replica}

sudo chown 1001 ./pg-*
