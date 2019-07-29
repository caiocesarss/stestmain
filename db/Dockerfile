FROM mysql:5.7

ENV MYSQL_DATABASE samtest
ENV MYSQL_ROOT_PASSWORD supersecret
ENV MYSQL_USER mysql
ENV MYSQL_PASSWORD supersecret
ENV DATABASE_HOST mysql

# Copiar conteúdo do diretório ./sql-scripts para imagem
# Os scripts de criação de tabelas e dados 
# serão executados durante a inicialização do container
COPY ./sql-scripts /docker-entrypoint-initdb.d/