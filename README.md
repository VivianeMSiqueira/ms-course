# Microsserviços Java com Spring Boot e Spring Cloud

Curso do professor Nélio Alves (https://www.udemy.com/course/microsservicos-java-spring-cloud/).

O projeto consiste na criação de um sistema composto por vários microsserviços que comunicam entre si de forma transparente, escalável e com balanceamento de carga.

![](https://github.com/VivianeMSiqueira/images/blob/main/microsserviços/diagrama.jpg)

Os microsserviços são registrados em um "Discovery Server" (Eureka), de modo que a comunicação entre eles é feita pelo nome do microsserviço. Além disso, as requisições são feitas em um API Gateway (Zuul), responsável por rotear e autorizar as requisições.

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/ms.png)

Autenticação e autorização, usando OAuth e tokens JWT, além de geração e teste dos containers Docker para deixar os microsserviços e as bases de dados aptos para implantação.



- Feign para requisições de API entre microsserviços

- Ribbon para balanceamento de carga

- Servidor Eureka para registro dos microsserviços

- API Gateway Zuul para roteamento e autorização

- Hystrix para tolerância a falhas

- OAuth e JWT para autenticação e autorização

- Servidor de configuração centralizada com dados em repositório Git

- Geração de containers Docker para os microsserviços e bases de dados (olhar branch docker)

### Criação de containers

- Conteiners:

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/Docker2OK.jpg)

- Imagens:

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/DokerImagesOK.jpg)

### Servidor Eureka

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/DockerRodandoOk.jpg)

### Testes no Postman

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/postmanOk.jpg)

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/2021-08-15%2000_51_41-Postman.jpg)

### Código

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/2021-08-15%2000_48_10-.jpg)

![](https://github.com/VivianeMSiqueira/images/blob/main/microsservi%C3%A7os/2021-08-15%2000_52_36-Configura%C3%A7%C3%B5es.jpg)
