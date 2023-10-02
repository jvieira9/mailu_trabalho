# mailu_trabalho
Basic configuration of a mailu server.

docker compose -p mailu up -d
docker compose -p mailu exec admin flask mailu admin admin xpto.local admin

Quando é criado um utilizador com "xpto.local" não é possível dar login. Devido às limitações do github, não é possível dar upload dos ficheiros de configuração para o repositório, então, é necessário criar o utilizador manualmente quando se levantar as máquinas.