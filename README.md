# airflow-jupyter

# Prerequisite
1. Docker 
2. Docker Compose

# Run
1. Deploy with docker compose
`docker-compose up -d`
2. check jupyter notebook token
`docker-compose logs notebook`
3. open in browser http://127.0.0.1:8888 for jupyter notebook
4. open in browser http://127.0.0.1:8181 for airflow (user : airflow, pass : airflow)
5. for undeploy `docker-compose down`

# Port Expose

- 8181 -> Airflow
- 8888 -> jupyter notebook

# Directory
- dags ->  airflow dags and jupyter notebok working dir
- plugins -> airflow plugins
- logs -> airflow logs
- postgres-db-volume -> postgres database data
