3proxy docker image
====

## How to run

```
docker run -d -it -name 3proxy -p 3128:3128 -v /path/3proxy/config:/etc/3proxy.cfg:ro googolmo/3proxy
```
