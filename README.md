# airflow
(based on vektorcloud/airflow)

Tiny Alpine image for running Apache Airflow

### Running

    docker run -p 8080:8080 -e AIRFLOW_INIT_DB=1 -v /var/run/docker.sock:/var/run/docker.sock --rm -it quay.io/vektorcloud/airflow:latest

### get worker and scheduler running

1. log in to the container and run: 
2. airflow worker & 
3. airflow scheduler & 
