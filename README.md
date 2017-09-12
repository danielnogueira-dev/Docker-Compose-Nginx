# Descrição

Docker com nginx


# Como uitilizar

1. Clone o repositório usando o comando:
   git clone https://github.com/danielnogueira-dev/Docker-Compose-Nginx

2. Entre na pasta docker-nginx-vhosts e copie o arquivo env-example para .env.
   cp env-example .env

3. Rode seu container:
   docker-compose up -d

4. Adicione os domínios no arquivo de hosts do windows.
   127.0.0.1 localhost
   127.0.0.1 api.dev

5. Abra no navegador
   http://localhost
   http://api.dev

6. Acessar o shell do container:
    docker exec -it nginx bash