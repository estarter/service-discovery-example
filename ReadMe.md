This is a test app for automatic service registering / discovery
with Spring framework and Eureka.

## How to run 

Run service (port 8761), client1 (port 8081, id: service1) and client2 (port 8082, id: service2)
using maven:
```bash
mvn spring-boot:run
``` 

Check out the status of services in central server: http://127.0.0.1:8761/

See that the client can see the server: http://localhost:8081/service-instances/service1 


## Credentials

Based on https://spring.io/guides/gs/service-registration-and-discovery/ 