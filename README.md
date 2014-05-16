docker-pdns
===========

docker-pdns is a PDNS instance with Sqlite3 backend.

# Build
$ sudo docker build --rm -t pdns .

# Run
$ sudo docker run -i -p 53:53/udp -p 8053:8053 -t pdns /bin/bash
