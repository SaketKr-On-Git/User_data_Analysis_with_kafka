# Realtime Data Streaming | End-to-End Data Engineering Project



## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. Everything is containerized using Docker for ease of deployment and scalability.

## System Architecture

![System Architecture](https://github.com/SaketKr-On-Git/User_data_Analysis_with_kafka/blob/main/Data%20engineering%20architecture.jpg)

The project is designed with the following components:

- **Data Source**: The pipeline retrieves random user data using the `randomuser.me` API.  
- **Apache Airflow**: Manages the orchestration of the pipeline and facilitates storing fetched data in a PostgreSQL database.  
- **Apache Kafka and Zookeeper**: Enable data streaming from PostgreSQL to the processing engine.  
- **Control Center and Schema Registry**: Provide tools for monitoring Kafka streams and managing schemas.  
- **Apache Spark**: Processes the data through its master and worker nodes.  
- **Cassandra**: Serves as the storage solution for the processed data.
  


## Technologies

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/SaketKr-On-Git/User_data_Analysis_with_kafka
    ```

2. Navigate to the project directory:
    ```bash
    cd e2e-data-engineering
    ```

3. Run Docker Compose to spin up the services:
    ```bash
    docker-compose up
    ```
