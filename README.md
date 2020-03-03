# Set Up

```console
$ docker-compose build
$ docker-compose up
$ docker exec -it app_ap bash
root@00000000000:/# curl -X PUT --data-binary @config.json --unix-socket /var/run/control.unit.sock http://localhost/config
```