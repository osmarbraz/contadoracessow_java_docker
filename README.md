# Contador de acesso em Java WEB com Docker Compose e Redis

Aplicação **Contador de Acesso WEB** desenvolvida em **Java** e executada em um container Docker.

## Sobre o projeto

- O projeto foi desenvolvido utilizando o **NetBeans**.
- O nome do projeto deve ser **contadoracessow_java_docker**.
- Utiliza o **Java 8**.
- Utiliza o **Apache Tomcat 9** como servidor de aplicações Web.
- Utiliza o **Apache Maven** para automatizar o processo de construção da aplicação.
- A aplicação é empacotada no formato **WAR (Web Application Archive)**.
- Utiliza o **Docker** para criar e executar os containers da aplicação e do banco de dados em memória.
- Utiliza o **Docker Compose** para definir e gerenciar os serviços da aplicação. 
- Utiliza o **Redis 7** como banco de dados em memória da aplicação. 

## Docker
 - Utilizer o terminal do Powershel em modo administrador.

### Para criar os conteiners e os serviços
 - ```docker compose up --build```

### Parar os serviços
 - ```docker compose down -v```

### Abra o navegador em:
 - http://localhost:8080/

### Remover as imagens
 - ```docker compose down --rmi all```

## Arquitetura do Sistema

![Arquitetura](arquitetura.png)

## Docker Hub
 - https://hub.docker.com/r/osmarbraz/contadoracessow_java_docker