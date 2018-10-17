Sample server and client Go files for running against RabbitMQ. Configured for TLS connectivity (see git@github.com:jbramlett-asapp/rabbitmq-ssl.git).

To run can do:

 	go run rpc_server
 	go run rpc_client


Included cert files are the ones used when setting up the RabbitMQ server (see above note on running secured RabbitMQ)