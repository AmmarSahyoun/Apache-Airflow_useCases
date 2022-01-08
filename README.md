# Apache-Airflow useCases


Productionalizing Pipelines with Apache Airflow.

Running various pipelines by docker-compose to get resilience data workflow.


*[x] Best practices:
- Develop DAG ->> SequentialExecutor 
- Starting in Production ->> LocalExecutor
- High Airflow usage ->> CeleryExecutor
- High spikes in Task usage ->> CeleryExecutor in Kubernetes

# 

````
docker-compose up --build
docker ps --format "table {{.Names}}:\t{{.Ports}}\t{{.Status}}"
docker-compose down.
````