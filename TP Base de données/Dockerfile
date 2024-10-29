FROM postgres:14.1-alpine

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr \
   POSTGRES_PASSWORD=pwd

   # Copier les scripts SQL dans le répertoire d'initialisation
COPY ./scripts /docker-entrypoint-initdb.d/  

