web:    bundle exec puma
worker: bundle exec rake resque:work QUEUE=*
redis:  redis-server /usr/local/etc/redis.conf
#clock:  bundle exec rake resque:scheduler
