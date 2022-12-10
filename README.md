# RabbitMQ-RPC-Client-Server-in-Java
Client - Server communication with RabbitMQ RPC

Install Docker in order to run RabbitMQ Server without having to install it

https://www.docker.com/products/docker-desktop/



After installing Docker, pull the RabbitMQ image and start the server by running these 2 commands in the command line:

docker pull rabbitmq

docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management



Start XAMPP, open phpmyadmin and import bank.sql


Start server and client
