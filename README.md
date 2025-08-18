# Naming Server
> Part of the **Currency Microservices Demo** — full system and run instructions:  
> https://github.com/Mehrdad-Ghaderi/currency-microservices-demo

This is the `naming-server` (Eureka) responsible for service discovery.

To run the full system and see how this service fits with others, please visit the umbrella repo linked above.



# Docker Images

---

https://hub.docker.com/u/mehrdadghaderi
- Currency Exchange Service
  - docker pull mehrdadghaderi/currency-exchange-service:0.0.1
- Currency Conversion Service
  - docker pull mehrdadghaderi/currency-conversion-service:0.0.1
- Eureka
  - docker pull mehrdadghaderi/naming-server:0.0.1
- API GATEWAY
  - docker pull mehrdadghaderi/api-gateway:0.0.1


# URLS

---
### Currency Exchange Service
- http://localhost:8000/api/v1/currency-exchange/from/USD/to/CAD

### Currency Conversion Service examples

[//]: # (- http://localhost:8100/api/v1/currency-conversion/from/USD/to/CAD/quantity/5)
- http://localhost:8100/api/v1/currency-conversion-feign/from/USD/to/CAD/quantity/5

### Eureka
- http://localhost:8761/

### Zipkin
- http://localhost:9411/

### API GATEWAY examples

- http://localhost:8765/api/v1/currency-exchange/from/USD/to/CAD

[//]: # (- http://localhost:8765/api/v1/currency-conversion/from/USD/to/CAD/quantity/5)
- http://localhost:8765/api/v1/currency-conversion-feign/from/USD/to/CAD/quantity/5
