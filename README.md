# Fake Shop com Prometheus e Grafana
https://github.com/fabricioveronez/fake-shop-desafio

## Variável de Ambiente
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.

### comando para pegar a senha do Grafana

kubectl get secret --namespace default grafana -o jsonpath="{.data.admin-password}" | base64 --decode; echo