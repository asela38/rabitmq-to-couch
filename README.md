# rabitmq-to-couch

Simple [Spring Boot](https://spring.io/projects/spring-boot) application to move data from [rabitMQ](https://github.com/asela38/rabitmq-to-couch.git) to [couchDB](http://couchdb.apache.org/)

Environment 

OS: Windows 7
Rabbit MQ: 3.6.14
Spring Boot Version: 2.0.5.RELEASE

Rabbit MQ
- Install Erlang: [http://www.erlang.org/downloads](http://www.erlang.org/downloads) 
- Install RabbitMQ: [https://www.rabbitmq.com/download.html](https://www.rabbitmq.com/download.html) 
- Enable RabbitMQ Management UI: [https://www.rabbitmq.com/management-cli.html](https://www.rabbitmq.com/management-cli.html)
```bash
	> rabbitmq-plugins enable rabbitmq_management
## to enable consistant hashing exchange 
	> rabbitmq-plugins enable rabbitmq_consistent_hash_exchange
```
- Now access Management Console : [http://localhost:15672](http://localhost:15672)
	- Default username/password : guest/guest

