FROM airbyte/integration-base-java:dev

WORKDIR /airbyte

ENV APPLICATION destination-mysql

ADD build/distributions/${APPLICATION}*.tar /airbyte

LABEL io.airbyte.version=0.1.15
LABEL io.airbyte.name=airbyte/destination-mysql
