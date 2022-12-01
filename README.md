## Nome do Projeto 

# Visão geral

O projeto é uma aplicação back-end com objetivo de demonstrar a produtividade de construir APIs utilizando os frameworks [Spring Boot](https://projects.spring.io/spring-boot), [Spring MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html) e [Spring Data](http://projects.spring.io/spring-data) em conjunto.

## Softwares / runtimes necessários
* JDK 17 
* Docker e Docker-Compose
* Git
* Como editor de código, recomenda-se o uso do IntelliJ


# APIs

O projeto disponibiliza algumas APIs em 3 contextos diferentes: Customer, Carriers e BilLs, onde utilizam o padrão Rest de comunicação, produzindo e consumindo arquivos no formato JSON.

Segue abaixo as APIs disponíveis no projeto:

#### Customer

 - /customers/search (GET)
 - /customers (GET)
 - /customers/paged/{page}/{size} (GET)
