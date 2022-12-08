<h2>Digital Innovation: Expert class - Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoque de cerveja, aprendendo a testar, unitariamente, uma API REST para o gerenciamento de estoque de cerveja. Desenvolver testes unitários para validar o sistema de gerenciamento de estoque de cerveja, e apresentar os testes unitários com JUnit e Mockito. Além disso, como desenvolver funcionalidades da API através da prática do TDD.


* Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
* Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. 
* Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
* TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```






