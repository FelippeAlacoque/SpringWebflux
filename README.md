# SpringWebflux
Programação assíncrona com Spring Webflux


**Configurações**
- Spring Webflux
- MongoDb

**Problema**
- A utilização do **Spring MVC** nos possibilita programar de maneira **síncrona** e **bloqueante**. Se sua aplicação recebe várias requisições de uma só vez, o Spring MVC fará o 
  processamento de uma requisição após a outra, ou seja, se o processamento da primeira requisição terminou, o processamento da segunda é iniciado, e assim por diante. Temos 
  então um gargalo no tempo de processamento.
- O **Spring Webflux** nos permite trabalhar de maneira reativa, ou seja, de maneira **assíncrona** e **não bloqueante**. Se sua aplicação recebe várias requisições de uma só vez,
  será possível que as requisições sejam processadas paralelamente. Portanto o processamento de uma requisição mais demorada não bloqueia o processamento das demais requisições
  que foram feitas.
