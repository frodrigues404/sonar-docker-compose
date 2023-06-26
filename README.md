# sonar-docker-compose
Feito por: <br>
Fernando Rodrigues Junior - 1121913 <br>
Guilherme Barea - 1127375 <br>
João Pedro Tondo - 1133671 <br>
Diego Trevisan - 1131769 <br>
Ronaldo Castelani - 1130584<br>

# SonarQube + PostgreSQL

O SonarQube é uma ferramenta de análise estatica de código.<br> Utilizamos o postgres para manter os dados da aplicação, que também pode subir sem um banco de dados, mas não é recomendado para ambientes produtivos.


# How To

$ sysctl -w vm.max_map_count=524288 // Essa configuração é padrão para a subida do Elasticsearch, se estiver utilizando o docker-desktop, pode ser necessário acessar o ambiente linux, para isso, utilize o comando wsl -d docker-desktop<br>

$ docker-compose up -d

