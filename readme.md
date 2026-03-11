# Containers

Project to sample Docker containers to agile a development environment.

- Jenkins
- Kafka
- MailHog
- MySQL 5.7
- MySQL 8.4
- Nginx
- NodeJS
- Oracle XE
- PHP 8.4
- PostgreSQL 17
- RabbitMQ
- Redis

# To start the containers

MySQL 5.7
``./containers --mysql57``

MySQL 8
``./containers --mysql84``

PostgreSQL
``./containers --postgres``

Redis
``./containers --redis``

Nginx
``./containers --nginx``

Jenkins
``./containers --jenkins``

Kafka
``./containers --kafka``

MailHog
``./containers --mailhog``

RabbitMQ
``./containers --rabbitmq``

PHP 8.2
``./containers --php``

Oracle XE
``./containers --oracle``

NodeJS
``./containers --nodejs``

All containers
``./containers --all``

# To stop the containers

Append `stop` to any command. Example:
``./containers --redis stop``
