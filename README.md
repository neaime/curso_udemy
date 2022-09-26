# curso_udemy
Kafka Producer and Consumer


###### 1º - No terminal, clone o projeto: 
```
git clone https://github.com/neaime/curso_udemy.git
```

###### 2º - Abra o terminar e digite o comando abaixo
```
docker-compose up
```

###### 3º - Com o postman ou Insomnia envie uma requisição do tipo POST para
```
localhost:8011/payments

Json:
{
		"id": 3,
		"idUser": 1,
		"idProduct": 1,
		"cardNumber": "45648684"
} 
```
