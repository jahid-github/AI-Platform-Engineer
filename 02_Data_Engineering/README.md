# Data Engineering

### Learning Resources
- [DataTalks.Club Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) — best free DE course
- [Data Engineering Course for Beginners](https://www.youtube.com/watch?v=PHsC_t0j1dU)

### 1. SQL & Databases (Foundation)
- [SQL](https://www.w3schools.com/sql/default.asp), [SQL Full Course for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus&t=1287s), [SQl with AI](./introduction-to-sql-with-ai.pdf)
- Relational Databases: PostgreSQL, MySQL, SQL Server
- [NoSQL (Irrelational Databases)](https://app.datacamp.com/learn/courses/introduction-to-nosql): [MongoDB (document)] (https://www.w3schools.com/mongodb/index.php), [Redis (cache)](https://www.youtube.com/watch?v=XCsS_NVAa1g), InfluxDB (time-series)
- Analytical: BigQuery, Snowflake, Azure Synapse, DuckDB
- Vector DBs: Weaviate, Pinecone (needed for RAG systems)

### 2. [Python for Data Engineering](https://www.w3schools.com/python/default.asp)
- File formats: CSV, JSON, Parquet, Avro, Delta
- Data wrangling with Pandas, PySpark, [Data Wrangling Cheat Sheet](./Data_Wrangling_Cheat_Sheet.pdf)
- API consumption and web scraping
- Scheduling and automation with Python scripts
- [Python Full Course for Beginners (13 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=Rq5gJVxz55Q&list=PLNcg_FV9n7qZGfFl2ANI_zISzNp257Lwn)

### 3. ETL / ELT Pipelines
- ETL vs ELT — when to transform before vs after loading
- Batch pipelines: extract → transform → load patterns
- Data modeling: Star Schema, Snowflake Schema, OBT
- dbt Core for SQL-based transformation layers, [dbt Fundamentals](https://courses.getdbt.com/courses/fundamentals), [dbt Core](https://github.com/dbt-labs/dbt-core)
- Data quality and validation (Great Expectations)
- Terraform (Language to inetrect with data)

### 4. Workflow Orchestration
-  [Apache Airflow](https://github.com/apache/airflow): DAGs, scheduling, monitoring
- Task dependencies, retries, SLAs, alerting
- HDFS: Hadoop Distributed File System for big data storage
- Alternatives: Prefect, Dagster

### 5. Stream Processing

- Apache Kafka [(Kafka Quickstart)](https://kafka.apache.org/quickstart): topics, producers, consumers, partitions, 
- [Apache Spark](https://spark.apache.org/): Distributed data processing at scale, Structured Streaming
- MQTT for IoT/sensor data (aligned with Phase 8 robotics)
- Use cases: real-time dashboards, fraud detection, event-driven ML

### 6. Cloud Data Platforms
- Azure: Data Lake Storage (ADLS), Data Factory (ADF), Synapse Analytics, [Azure CLI Cheat Sheet](./Azure_CLI_Cheat_Sheet.pdf)
- GCP: BigQuery, Cloud Storage, Dataflow, Pub/Sub, Vertex AI
- [Databricks](https://www.youtube.com/watch?v=oA90QLr_PsM&list=PLNcg_FV9n7qZWchr-GE5iPPBmOjiffK6O): Delta Lake, Spark compute, Unity Catalog, [Databricks Academy](https://www.databricks.com/learn/training/home)
- [GitHub Actions](https://campus.datacamp.com/courses/cicd-for-machine-learning/introduction-to-continuous-integrationcontinuous-delivery-and-yaml?ex=7): CI/CD for data pipelines

### 7. Containerization & Orchestration
- Docker: containerize pipelines and services
- Docker Compose: multi-service local environments
- Kubernetes: deploying and scaling data services
- NGINX: reverse proxy for data APIs

### 8. MLOps & Data Versioning
- MLflow: experiment tracking, model registry
- DVC: data versioning alongside Git
- Weights & Biases: experiment visualization

## Data Engineering Project
1. Smart Retail Sales & Inventory Analytics Pipeline in Snowflake