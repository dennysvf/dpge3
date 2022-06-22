# Chatbot

### Instalação

Siga os passos abaixo para instalação e execução do sistema Chatbot.

##### Baixe o clone do repositório:

```sh
$ git clone https://codigos.ufsc.br/chatbot/chatbot.git
```

##### Acesse a pasta:

```sh
$ cd chatbot
```

##### Execute o instalador para baixar o repositório de cada serviço (api, admin, frontend):

```sh
$ ./download.sh
```

##### Configure o arquivo `docker-compose.yml`
Altere as variáveis de secrets e senhas de banco.


##### Execute a aplicação:

```sh
$ docker-compose up
```


##### Acesse os serviços através das urls abaixo:

* http://localhost:3000 (Chatbot-frontend)
* http://localhost:3001 (Chatbot-admin)
* http://localhost:3002 (Chatbot-api)
* http://localhost:3003 (Adminer)


O usuário do painel administrativo é criado durante a execução, com base nos valores das variáveis `ADMIN_USERNAME` e `ADMIN_PASSWORD`. Os valores default são `admin` / `123456`.