# 1. Start the Services using docker file: 

    docker compose up

# 2. Start the Services using docker file: 

  If everything goes well, you can access the following services at given location:

  Discovery Server - http://localhost:8761
  Config Server - http://localhost:8888
  AngularJS frontend (API Gateway) - http://localhost:8080
  Customers, Vets and Visits Services - random port, check Eureka Dashboard
  Tracing Server (Zipkin) - http://localhost:9411/zipkin/ (we use openzipkin)
  Admin Server (Spring Boot Admin) - http://localhost:9090
  Grafana Dashboards - http://localhost:3000
  Prometheus - http://localhost:9091