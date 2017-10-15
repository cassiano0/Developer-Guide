# Developer-Guide

## Comandos Github
***Pegar branch do servidor***
    
    git checkout --track origin/nome_da_branch
    
***Adicionar arquivos modificados/deletados/adicionados***
    
    git add .
    
O '.' aqui é um coringa e irá adicionar todos arquivos para o commit. Se desejar enviar um arquivo especifico, deverá substituir o '.' pelo caminho completo para o arquivo.

***Commit***

    git commit -m "digite sua mensagem aqui"
    
Lembrando que a mensagem deve estar obrigatóriamente entre "

***Pegando commits do servidor***

    git pull
    
***Enviando commits para o servidor***

    git push
    
***Mudando de branch***

    git checkout nome_da_branch
    
# Comandos Laravel
***1º comando após clonar repositório***

    composer install
    
ou

    php composer.phar install

***Atualizar banco de dados***
    
    php artisan migrate
