# Apache-Airflow_useCases
Running various pipelines by docker-compose.

Create resilient data pipelines and scale it :+1:


-[ ] Best practices:
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