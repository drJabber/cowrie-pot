FROM cowrie/cowrie

USER root

RUN  apt update && \
     apt install -y libmariadbclient-dev python-mysqldb

USER cowrie

ENTRYPOINT ["cowrie"]
CMD ["start -n"]
EXPOSE 2222 2223
