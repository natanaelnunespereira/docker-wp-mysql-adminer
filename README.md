# Docker - WordPress e MySQL

## Pré-requisitos

- Possuir o [Docker](https://docs.docker.com/get-docker/) instalado em sua máquina.
- Realizar a instalação do [Docker Compose](https://docs.docker.com/compose/install/).

## Docker Compose
O Docker Compose é uma ferramenta  desenvolvida para auxiliar a definir e compartilhar aplicativos com inúmeros contêineres. Utilizando o Compose, pode-se criar um arquivo YAML/YML para definir os serviços e com apenas um único comando, é possível rodar todos os contêineres ou para-los.  

## Ambientação da aplicação

Após os processos de instalação citados acima, é realizado a aplicação do arquivo **docker-compose.yml**.    

Para subir a aplicação digite o comando: `# docker-compose up -d`.  
Para verificar a criação digite o comando: `# docker-compose ps`.  
Caso queira atestar a criação dos containers, digite o comando `# docker container ls`.  
