# Proyecto Microservicios con arquitectura hexagonal, diseño API-FIRST (OAS) --> PcTallerProject
This repo contains links to all microservices that make this project


## Person data service
### https://github.com/JosepeDevs/PcRepairPersonData

## Authentication service
### https://github.com/JosepeDevs/PcRepairAuthService

## API-Gateway service
### https://github.com/JosepeDevs/PcRepairAPIGateway

## Eureka Server service
### https://github.com/JosepeDevs/PcRepairEurekaServerService



### TODAVÍA EN DESARROLLO
Este proyecto implementa microservicios utilizando una arquitectura hexagonal, API gateway, Eureka y CQRS. Fue planificado y desarrollado por JosepeDevs 


## Tecnologías Utilizadas

- **Java**
- **Spring**
- **Spring Boot**
- **Spring Cloud**
- **Javascript Web Token JWT**
- **Swagger: Swagger-UI, Swagger-codeGen, Swagger ReDoc**
- **API Gateway**
- **Junit**
- **Mockito**
- **Eureka**
- **CQRS**

## Estilo 
- **Microservicios**
- **Arquitectura hexagonal**
- **Desarrollo API-first (OpenAPI : OAS)**
- **Clases y microservicios aplicando principios SOLID**
- Excepciones propias, manejadas globalmente con un @ControllerAdvise, para código más limpio y control centralizado de errores.
- Uso de opcionales de Java
- Value Objects con validadores en los constructores
- Librería Lombok para mayor productividad en clases repetitivas (constructores, getters, setters...)

## Infraestructura

La infraestructura del proyecto incluye:

- **AWS RDS --> PostgreSQL (para las escrituras: commands)**
- **API HTTP REST RestFul**
- **Postman para peticiones HTTP**
- **MongoDB para las lectuas (queries)**

## Disclaimer

Este proyecto sirve como ejemplo de cómo implementar CQRS y otros patrones en un entorno real. Sin embargo, cabe destacar que la adición de estos patrones aumenta la complejidad el proyecto. Solo donde exista un beneficio claro lo implementaría (p.e. si hay mucha carga en las lecturas o se usan modelos complicados que implican multiples JOIN de una base de datos) puede merecer la pena aplicar el patrón CQRS, ya que con su planteamiento permite una mejor escalabilidad y mejor tiempo de respuesta. En este proyecto, se ha aplicado CQRS para probarlo, para un proyecto con este alcance realmente no haría falta.

