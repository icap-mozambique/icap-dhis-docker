FROM postgis/postgis:10-3.0

LABEL maintainer="skm2180@cumc.columbia.edu"

ENV POSTGRES_USER=admin 
ENV POSTGRES_PASSWORD=admin
ENV POSTGRES_DB=dhis2
ENV POSTGRES_MULTIPLE_EXTENSIONS=postgis

ADD localtime /etc/localtime
ADD postgresql.conf /etc/postgresql/postgresql.conf

VOLUME /opt/dhis/data

EXPOSE 5432