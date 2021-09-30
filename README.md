<h2>Sistema de gerenciamento de pessoas em API REST com Spring Boot</h2>

API REST criada com Java 11 e com deploy no Heroku.

https://peopleapi-restful-level2.herokuapp.com/


| URI                 | METHOD        | REQUEST STREAM |  REQUEST RESPONSE  | STATUS CODE  |
| ------------------- | ------------- | -------------- | ------------------ | ------------ |
| api/v1/people       | GET           | n/a            | People collection  | 200/404      |
| api/v1/people/{id}  | GET           | n/a            | Person             | 200/404      |
| api/v1/people       | POST          | person info    | Person             | 201/404      |
| api/v1/people/{id}  | PUT           | person info    | Person             | 200/404      |
| api/v1/people/{id}  | DELETE        | n/a            | n/a                | 200/404      |


<h3>Data Model</h3>

![Data model](https://github.com/jackelinenascimento/peopleapi/blob/main/images/modelo-dados.PNG)


<h3> Para executar o projeto no terminal, faça o seu clone e então digite o seguinte comando: </h3>

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```
