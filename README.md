# Projeto Final de Programação Dinâmica para WEB

Observação: código está na master

## Instruções para utilização

1. Instalar o XAMP e o PHP. (https://www.apachefriends.org/pt_br/download.html)

2. Ativar o servidor do XAMP para utilização do localhost
  ![image](https://user-images.githubusercontent.com/49880853/145239940-43b8f9c1-49c0-444e-8998-042db4dcf280.png)

3. Instalar o composer. (https://getcomposer.org/download/)

4. Criar um arquivo na raiz do projeto chamado composer.json com o seguinte código:

  {
    "require": {
        "twig/twig": "^3.3"
    }
}

5. Baixar o composer.phar (https://getcomposer.org/composer.phar) e colar na raiz do projeto.
 
6. Abrir um CMD na pasta raiz do projeto e executar o seguinte comando:
    
    php composer.phar install
    
    composer require twig/twig
    
O projeto está instalado.

Para visuzalização de dados do banco de dados:

1. Acessar o localhost/phpmyadmin e criar um banco de dados com os seguintes parâmetros:
    Uma tabela chamada postagem:
    
    ![image](https://user-images.githubusercontent.com/49880853/145240982-f68efb6e-c15b-41ec-8199-40604d87d34b.png)

    Uma tabela chamada comentario:
    
    ![image](https://user-images.githubusercontent.com/49880853/145241056-7a637eab-3148-426f-ba79-031bfda5a3ee.png)
    
2. Após feito isso, realizar um insert na tabela via MyPHPAdmin e utilizar o app.



Problemas:

- Caso haja algum problema de abertura do banco, verifique o arquivo Connection.php se o nome do banco está correto.
- Verificar os links de localhost se estão semelhantes com o nome da pasta que você criou. O nome padrão é http://localhost/projeto_crud_mvc/site-php-mvc-crud/


Muito obrigado!
