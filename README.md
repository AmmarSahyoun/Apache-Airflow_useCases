# Apache-Airflow_useCases
Running various pipelines by docker-compose.
* Create resilient data pipelines.
* Apply advanced techniques to scale the pipelines.

-Run docker image: ~ docker-compose up --build
-Check running containers: ~ docker ps --format "table {{.Names}}:\t{{.Ports}}\t{{.Status}}"
-shut down comtainers: ~ docker-compose down