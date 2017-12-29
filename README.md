<h1>Docker com PHP  7.1 e MySQL 5.7 com phpMyAdmin</h1>

<h2>Descrição</h2>
<p>O docker contém o PHP 7.1 e o MySQL 5.7 para facilitar , ambos rodando em cma do webser apache 2, este projeto ainda se encontra na fase inicial, caso esteja disposto a contribuir fique a vontade para fazer seu pull request.</p>

<h2>Tutorial</h2>
    <ul>
        <li>Instale o docker que atende o seu S.O , no caso vá em 
        https://www.docker.com/ em seguida get Docker e selecione o seu S.O é siga as instruções.</li>
        <li>Faça o clone deste repositório.</li>
        <li>Por fim vá dentro da pasta do docker e rode o comando docker-compose up.</li>
        <li>Para começar a trabalhar é so criar uma pasta de sua preferencia e comçar a com arquivos .php :).</li>
        <li>Para acessar o MySQL é so acessar o seguint host:http://localhost:8080/.</li>
    </ul>

<h2>Comandos úteis</h2>
    <ul>
        <li>docker-compose up : sobe os containers.</li>
        <li>docker-compose down : destroi os containers.</li>
        <li>docker-compose stop : pausa os containers.</li>
        <li>docker ps : lista os containers ativos.</li>
        <li>docker search NOME_DO_CONTAINER : Procura imagens do container.</li>
        <li>docker exec -it NOME_DO_CONTAINER sh : acessa o container.</li>
        <li>docker rm NOME_DO_CONTAINER : Remove um container.</li>
        <li>dokcer kill NOME_DO_CONTAINER : mata os container indicado.</li>
    </ul>
<p>Obs:Em alguns casos quando você tem o mysql instalado na sua maquína , ou algum web server é necessario parar os serviços deles devidos as portas utilizas por ambos.</p>