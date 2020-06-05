# my-docker-setup
docker setup for local development

This is my setup for laravel project local development  
Simply copy .env.example to .env  
then configure the exposed PORT of each container, PROJECT_PREFIX, and image version  

```
to run for first time
$ docker-compose build
$ docker-compose up -d
```

```
to shutdown
$ docker-compose stop
or
$ ./stop
```

```
to start
$ docker-compose start
or
$ ./start
```

```
to use php cli or mysql cli
$ ./php
$ ./mysql
```
