# rabbitmq

build
```
docker build -rm -t rabbitmq:centos6 .
```

run
```
docker run -p 5672:5672 -p 15672:15672 --name rabbitmq -d rabbitmq:centos6
```

