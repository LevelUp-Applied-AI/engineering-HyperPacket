# Docker Notes — Day 9

## Docker Version

docker -v
Docker version 29.2.1, build a5c7197

## Hello World Test

docker run hello-world

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:

1.  The Docker client contacted the Docker daemon.
2.  The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
3.  The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
4.  The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
$ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
https://hub.docker.com/

For more examples and ideas, visit:
https://docs.docker.com/get-started/

## Postgres Container

2026-03-03 07:44:25.682 UTC [1] LOG: listening on IPv6 address "::", port 5432
2026-03-03 07:44:25.709 UTC [1] LOG: listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
2026-03-03 07:44:25.741 UTC [29] LOG: database system was shut down at 2026-03-03 07:18:03 UTC
2026-03-03 07:44:25.769 UTC [1] LOG: database system is ready to accept connections

## Stop and Restart

2026-03-03 07:45:56.619 UTC [1] LOG: listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
2026-03-03 07:45:56.656 UTC [29] LOG: database system was shut down at 2026-03-03 07:45:48 UTC
2026-03-03 07:45:56.681 UTC [1] LOG: database system is ready to accept connections

## Issues Encountered

None

---
