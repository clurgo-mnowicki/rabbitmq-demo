# Spring with RabbitMQ
 Demo project for `@RabbitListener`/`@RabbitHandler` implementation.
1. Run RabbitMQ container
> docker run -d -p 5674:5672 -p 15674:15672 --name rabbitmq-demo rabbitmq:3-management
2. Run application
3. Call the controller with simple POST request to `localhost:8080/foo` or `localhost:8080/bar`.
```json
    "a": "some value",
    "b": "other value",
    "d": "another one"
```
