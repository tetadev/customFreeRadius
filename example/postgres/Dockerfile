FROM ibrahimiii/freeradius-bnet:0.1-pg-alpine
ENV CON="postgres://postgres:SomeSecretPassword@postgres:5432/postgres"
COPY config/sql config/sql
CMD [ "-d migrate=true -log=true" ]
