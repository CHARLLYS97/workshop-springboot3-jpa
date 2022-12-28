# WEB SERVICES API REST

## Modelo de domínio
![Diagrama de Classes](assets/img/diagram.png)

> Workshop SpringBoot é uma aplicação back-end construída durante o curso [Java COMPLETO Programação Orientada a Objetos +Projetos](https://www.udemy.com/course/java-curso-completo "Site do Curso").

A aplicação consiste em uma API de serviços web com integração ao banco de dados Postgresql. Na aplicação podemos cadastrar, remover e atualizar produtos, usuários e os pedidos feitos pelos clientes.
 
## Diagrama de objetos
![Diagrama de Objetos](assets/img/object_diagram.png)

### Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você precisa compreender a linguagem Java, conceitos de POO (Encapsulamento, herança e polimorfismo)
* Você precisa compreender alguns projetos do ecossistema Spring
* Você precisa compreender o que é API Rest

### Tecnologias empregadas
- [x] Spring boot
- [x] Spring web
- [x] Spring JPA/Hibernate
- [x] Object Relational Mapping (ORM)
- [x] API Rest
- [x] Banco de dados H2
- [x] PostgreSQL
- [x] Postman
- [x] Heroku

## Estrutura [Banco de Dados H2](https://en.wikipedia.org/wiki/H2_(DBMS))

Banco de dados totalmente contruído com ORM
![Banco de Dados](assets/img/bd_h2.png)
<center> 
    <b>Banco de dados em memória</b>
</center>
<br>

### Imagens APIs Rest no [Postman](https://en.wikipedia.org/wiki/Postman_(software))
#### Post
![POST](assets/img/api_post.png)

#### Get
![GET](assets/img/api_get.png)

#### Put
![PUT](assets/img/api_put.png)

#### Delete
![DELETE](assets/img/api_delete.png)

#### PostgreSQL
![PostgreSQL](assets/img/Script.sql.png)


Para instalar o projeto, siga estas etapas:

Linux, macOS e Windows:
```
<git clone git@github.com:CHARLLYS97/workshop-springboot3-jpa.git >
```
#### Próximo passo
* Importe o projeto na IDE _**Spring Tools Suite**_, e execute a classe 
``
CourseApplication.java
`` dentro da pasta `src/main/java/com/educandoweb` | [Acessar pasta](src/main/java/com/).
