aria2-server
============

```shell
docker pull pihizi/aria2
docker run --name pihizi-aria2 \
    -v /dev/log:/dev/log \
    -p 8888:8888\
    -d pihizi/aria2

```
