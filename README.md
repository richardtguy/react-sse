
# react-sse

## Start local REDIS server
```
redis-server /usr/local/etc/redis.conf
```

## Start web application
```
gunicorn sse:app --worker-class gevent --bind 127.0.0.1:8000
```
