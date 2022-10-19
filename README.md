# Docker - WordPress e MySQL

## Pré-requisitos

- Possuir o [Docker](https://docs.docker.com/get-docker/) instalado.
- Realizar a instalação do [Docker Compose](https://docs.docker.com/compose/install/).

## Docker Compose
O Docker Compose é uma ferramenta desenvolvida para auxiliar a definição e compartilhamento de aplicações com um ou mais containers. É criado um arquivo YAML para definição dos serviços e, com apenas um único comando, é possível gerar todos os containers ou pará-los.  

## Ambientação da aplicação

Após os processos de instalação citados, é realizada a aplicação do arquivo [docker-compose.yml](./docker-compose.yml). Esse arquivo define os serviços WordPress e MySQL. Abaixo constam alguns comandos utilizados ao decorrer do processo.    

- Subir a aplicação: `# docker-compose up -d`.
- Verificar a criação do compose: `# docker-compose ps`.
- Averiguar os logs do compose: `# docker-compose logs -f`.
- Atestar a criação dos containers: `# docker container ls`.
- Verificar a criação dos volumes: `# docker volume ls`.
- Interromper e remover os containers criados pelo compose: `# docker-compose down`.

## Processo de mudança de nome do domínio "localhost"

O principal uso deste tipo de domínio é para testes de *websites* antes da propagação dos DNSs na *web*. Abaixo segue o processo:  

### Windows
Navegar ao diretório: `# cd C:\WINDOWS\system32\drivers\etc\`.  
Atribuir uma nova linha no arquivo **hosts** contendo o IP do *host* e o nome do domínio.  

### Linux
Alterar o arquivo: `# vim /etc/hosts`.  
Atribuir uma nova linha no arquivo contendo o IP do *host* e o nome do domínio.
