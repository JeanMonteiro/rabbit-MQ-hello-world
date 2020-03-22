# rabbit-MQ-hello-world
simple hello world with node + rabbitMQ

this project assumes that you have rabbitMQ installed and running on localhost:5672 (https://www.rabbitmq.com/download.html)

First, run the file send.js, it will create a queue (if it doesn't exists) with name "hello", then, run receive.js, it will get the created queue (or create if it doesnt exists), will comsume and print the message sended by the send.js.
