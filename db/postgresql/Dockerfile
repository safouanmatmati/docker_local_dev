ARG POSTGRES_VERSION=10.5

FROM postgres:${POSTGRES_VERSION}-alpine

COPY add-conf.d.sh /docker-entrypoint-initdb.d/
COPY conf.d /srv/postgresql/conf.d
