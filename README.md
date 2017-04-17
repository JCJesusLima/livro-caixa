# Livro Caixa 
Controle de Livro Caixa
=======
*(for English read below)*

Livro Caixa é um sistema simples baseado em PHP/MySQL para o controle mensal de seu caixa.
Foi baseado no sistema Livro Caixa de "Felipe Ismael Barth" (fibbarth) - https://github.com/fibbarth

Algumas melhorias:
* Inclusão da Bootstrap e modificação de alguns códigos para tentar trazer de forma simples o aplicativo para uso no mobile.

﻿Intruções de instalação e configuração
---------------------------------------

---------------------------------------
O arquivo para criação do banco de dados é o livro_caixa.sql. 
---------------------------------------

---------------------------------------
Dentro da pasta raiz do projeto edite o arquivo 'config.php' e altere as configurações conforme o seu ambiente:

//Configuração do Banco de dados
$host = "localhost";
$user = "root";
$pass = "";
$d_b = "livro_caixa";

//Título do seu livro Caixa, geralmente seu nome
$lc_titulo="Alexandre LLemes";

//Autenticação simples
$usuario="admin";
$senha="123";

---------------------------------------
Dados de acesso
Email: admin
Senha: 123
---------------------------------------


### Frameworks/Bibliotecas
* [twbs/bootstrap](https://github.com/twbs/bootstrap) 
* [jquery/jquery](https://github.com/jquery/jquery) 
* [jquery/jquery-ui](https://github.com/jquery/jquery-ui) 

### Requerimento
* PHP >= 5.4.0 <= 5.6
* MySQL

### Créditos
* Alexandre LLemes - alexandre.llemes@gmail.com
