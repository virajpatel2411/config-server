# config-server
Demo Spring Config Server


For microservice specific properties file the name should be <microservice-name>.extn

extn can be yml or properties

Each microservice will have specific properties file and will read from that through a single config server

For reading it using api call, use http://localhost:<port>/<name of properties file>/<spring profile name>
