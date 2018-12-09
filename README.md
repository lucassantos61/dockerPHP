# Docker com PHP  7.1 e MySQL 5.7 com phpMyAdmin

## Descrição
O docker contém o PHP 7.1 e o MySQL 5.7 para facilitar , ambos rodando em cma do webser apache 2, este projeto ainda se encontra na fase inicial, caso esteja disposto a contribuir fique a vontade para fazer seu pull request.

## Tutorial
   - Instale o docker que atende o seu S.O , no caso vá em https://docs.docker.com/install/ em seguidaselecione o seu S.O é siga as instruções.
   - Faça o clone deste repositório.
   - Por fim vá dentro da pasta do docker e rode o comando docker-compose up.
   - Para começar a trabalhar é so criar uma pasta de sua preferencia e colocar seus arquivos .php :).
   - Para acessar o MySQL é so acessar o seguint host:http://localhost:8080/.

## Comandos úteis
    - docker-compose up : sobe os containers.
    - docker-compose down : destroi os containers.
    - docker-compose stop : pausa os containers.
    - docker ps : lista os containers ativos.
    - docker search NOME_DO_CONTAINER : Procura imagens do container.
    - docker exec -it NOME_DO_CONTAINER <sh>/<bash> : acessa o container.
    - docker rm NOME_DO_CONTAINER : Remove um container.
    - dokcer kill NOME_DO_CONTAINER : mata os container indicado.
Obs:Em alguns casos quando você tem o mysql instalado na sua maquína , ou algum web server é necessario parar os serviços deles devidos as portas utilizadas por ambos.
