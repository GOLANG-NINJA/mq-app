# Simple RabbitMQ client & server example

In order to run RabbitMQ you can use docker:

`docker run -it --rm --name rabbitmq -p 5672:5672 rabbitmq`

Start server (sender):

`go run cmd/server/server.go`

Start client (reciever): 

`go run cmd/client/client.go`