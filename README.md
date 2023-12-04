[h1]Alunos[/h1]
Murilo Matheus Ruiz
Carlos Eduardo da Silva

Descrição:
Trabalho realizado para a matéria de Web-Servidor com o intuito de apresentar o terceiro projeto para avaliação. O projeto trata-se de uma api que realiza consultas, inserções, atualizações e deleções no banco de dados do sistema da pizzaria dos outros projetos.

Documentação:
Utilizamos o Xampp para inicializarmos o MySQL, desta forma, o Apache e o MySQL precisam estar ativos;
Para criação do banco de dados precisa colocar no CMD o comando "composer install" para a criação do autoload e o "php artisan migrate" estando na pasta da API;
e após isso, precisa-se utilizar o comando "php artisan serve" no cmd para ligar o servidor.

Para o teste da API utilizamos o client http Insomnia;
Será necessário importar o arquivo lilcoxas-insomniaimport.json para execução dos testes;
Devido a autenticação necessária para as rotas somente os testes de registro e login foram automatizados;
Para as demais rotas, faz-se necessário utilizar um token já criado via registro ou login.

Features:
Criação do banco de dados;
CRUD;
Rotas estruturadas;
Autenticação;

Atividades:
Murilo
Criação da rota e controller de Flavor e Size;
Padronização de mensagens de retorno para todos os métodos dos controllers;
Tratamento de erros de todos os métodos dos controllers.
Autenticação API Token via Sanctum;

Carlos
Criação das Migrations;
Criação dos Models;
Criação da rota e controller de Dough e Sauce;
Realização do README.
Validação de testes por meio do Insomnia.
