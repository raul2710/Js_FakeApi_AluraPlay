<p align="center"> <img src="https://imgur.com/J3hD21O.png" alt="Javascript: criando requisições"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Página inicial e formulário de cadastro de vídeos da AluraPlay, uma plataforma de compartilhamento de vídeos.</p>

## Tecnologias utilizadas durante o curso
* Javascript
* NodeJS
* Json-server

## Tecnologias utilizadas no projeto
* HTML
* CSS

## Screenshots
![Screenshot da tela inicial do AluraPlay](https://imgur.com/aymxEsh.png)
![Screenshot da tela do formulário do AluraPlay](https://imgur.com/ShNADf2.png)

# Atualizações
Para instalar o json-server:
- npm i -g json-server
- npm install --global json-server

Nas aulas em questão o mais recente json-server não funciona, tendo que ser instalado o da versão do vídeo 0.17.0
- npm i -g json-server@0.17.0

Abaixo o código para desinstalar o json-server
- npm uninstall -g json-server

Assim agora podemos executar o comando abaixo para monitorar o arquivo db.json
- json-server --watch db.json
- json-server -w db.json