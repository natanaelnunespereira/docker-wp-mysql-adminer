# Docker - WordPress e MySQL

## Pré-requisitos

- Possuir o [Docker](https://docs.docker.com/get-docker/) instalado.
- Realizar a instalação do [Docker Compose](https://docs.docker.com/compose/install/).

## Docker Compose
O Docker Compose é uma ferramenta desenvolvida para auxiliar a definir e compartilhar aplicações com inúmeros containers. Pode-se criar um arquivo YAML para definição dos serviços e, com apenas um único comando, é possível gerar todos os contêineres ou pará-los.  

## Ambientação da aplicação

Após os processos de instalação citados acima, é realizado a aplicação do arquivo **docker-compose.yml**.    

Para subir a aplicação digite o comando: `# docker-compose up -d`.  
Para verificar a criação digite o comando: `# docker-compose ps`.  
Caso queira atestar a criação dos containers, digite o comando: `# docker container ls`.  
