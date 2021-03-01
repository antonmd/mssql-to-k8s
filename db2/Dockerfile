FROM mcr.microsoft.com/mssql/server:2019-CU9-ubuntu-16.04
USER root
COPY . /tmp/

RUN chmod +x /tmp/db-init.sh
CMD /bin/bash ./tmp/entrypoint.sh