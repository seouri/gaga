gaga
====

```
$ brew install redis
$ redis-server /usr/local/etc/redis.conf
$ cp config/database.yml.mysql config/database.yml
$ rake db:setup
$ foreman start
```
