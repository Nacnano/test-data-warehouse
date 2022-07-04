# MAL Data Warehouse
- A repository for automatic data warehouse codes for me using Apache Airflow and Github Action 

- So, the purposes of this project is mostly to train my Data Engineer skills

## Requirements 

1. Docker installed (the rest can be installed  using docker anyway)

2. 4 GB RAM avalible (more than 8 GB is highly recommended)

3. Enable your Docker RAM usage to >=4 GB 

### Warning : This may cause lag or crash your device when you start running Docker


## How to Run (For Ubuntu)

1. Initialize Airflow from Docker

```
docker-compose up airflow-init
```

2. Build everything from Apache Airflow
```
docker build -t apache/airflow:2.1.4 .
```

3. Run Airflow
```
docker-compose up
```

Note (Not Recommended): if you can't run as regular user, try using "sudo" to run as a root user.

## User Interface 

While running, Airflow UI will be in localhost port 8080 (http://localhost:8080/)
