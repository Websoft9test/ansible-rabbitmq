# Start or Stop the Services

These commands you must know when you using the RabbitMQ of Websoft9

## RabbitMQ

```shell
sudo systemctl start rabbitmq-server
sudo systemctl stop rabbitmq-server
sudo systemctl restart rabbitmq-server
sudo systemctl status rabbitmq-server

# you can use this debug mode if RabbitMQ service can't run
rabbitmq-server console
```