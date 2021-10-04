# People API
API REST created with Java 11 and deployed on Heroku


https://peopleapi-restful-level2.herokuapp.com/


| URI                 | METHOD        | REQUEST STREAM |  REQUEST RESPONSE  | STATUS CODE  |
| ------------------- | ------------- | -------------- | ------------------ | ------------ |
| api/v1/people       | GET           | n/a            | People collection  | 200/404      |
| api/v1/people/{id}  | GET           | n/a            | Person             | 200/404      |
| api/v1/people       | POST          | person info    | Person             | 201/404      |
| api/v1/people/{id}  | PUT           | person info    | Person             | 200/404      |
| api/v1/people/{id}  | DELETE        | n/a            | n/a                | 200/404      |


### Data Model

![Data model](https://github.com/jackelinenascimento/peopleapi/blob/main/images/modelo-dados.PNG)

### Help Need it

If you want to contribute, please submit a PR! Thanks!