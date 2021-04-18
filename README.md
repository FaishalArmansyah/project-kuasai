# project-kuasai

yaml:
docker-compose.yml        --> untuk env. local dev
docker-compose-stack.yml  --> untuk env. production

folder:
secret    --> password secret mysql
web       --> Dockerfile & file-web dari service 'web'
mysql     --> Dockerfile & dump.sql dari service 'mysql'
pma       --> Dockerfile dari service 'pma'
proxy     --> Dockerfile & nginx.conf dari service 'proxy'
