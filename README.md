# rabbitmq
example rabbitmq using producer in JS and consumer in python with rabbit using docker

Following this tutorial it is possible to see the creation process in detail;

https://www.architect.io/blog/2021-01-19/rabbitmq-docker-tutorial/

steps:

clone -> docker pull rabbitmq:3-management -> docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3-management

to check RabbitMQ

localhost:15673 -> user guest -> password guest

to check Producer

npm start -> http://localhost:3000/message

to check Consumer

run -> python consumer.py

;)
