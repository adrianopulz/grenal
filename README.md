# GreNal
`v1.0`

## Informações do Projeto
Projeto desenvolvido para a apresentação na Drupal Day POA 2015. É um site em Drupal 8, que permite a publicação de artigos.
Todos os artigos são exportados em formto JSON, através do módulo do Drupal RESTful Web Services e Serialization.
Com isso é possível alimentar um App, no caso, feito em Ionic, com o objetivo de demonstrar como utilizar o Drupal com um gerenciador de conteúdo para outra aplicação.

## Envolvidos
* [Adriano Pulz](mailto:adrianopulz@gmail.com)

## Utilizando o Projeto
Clone o projeto. Crie um banco e importe do arquivo na raiz, chamado latest.sql.
Crie um arquivo chamado settings.local.php onde deverá conter as suas informaçoes de conexão com o banco de dados.
Apenas é necessário editar o nome do banco, usuário e senha.
Na pasta sites/default existe um arquivo de exemplo, chamado settings.exemple.php
