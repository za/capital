FROM redis:7.2.5

COPY ./dump.rdb /data/dump.rdb
ENTRYPOINT ["redis-server", "--dbfilename", "dump.rdb", "--dir", "/data"]