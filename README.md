# airflow-docker
## Simple airflow Dockerfile

Build

git clone
cd airflow-docker
docker build ./ -t airflow

docker start -d -p 8080:8080 airflow 

ToDo

- external Postgres / MySQL
- LocalExecutor(n)
- celery/redis clusterization
