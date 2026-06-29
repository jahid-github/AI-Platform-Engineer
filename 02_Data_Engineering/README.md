# Data Engineering
- Beginner: [Learning SQL, 3rd Ed.](https://drive.google.com/file/d/14Go3hhyl4yemA4JWBuRQmMbRUB9C65Pm/view?usp=drivesdk)
- Beginner–Intermediate: [Fundamentals of Data Engineering](https://drive.google.com/file/d/1GGr6Looa8cXZPRGnCWMQdqh9pX2tLWfI/view?usp=drivesdk)
- Intermediate: [Designing Data-Intensive Applications](https://drive.google.com/file/d/1EeBHEkL9axAolvUX3Yr1NRNOShWXYTGq/view?usp=drivesdk)
- Intermediate: [Python for Data Analysis, 3rd Ed.](https://drive.google.com/file/d/1Lw2FhIn-Piao7TVM__uyV_5RkZMQsTdx/view?usp=drivesdk)
- Intermediate–Advanced: [Streaming Systems](https://drive.google.com/file/d/1yYG1dvwY3wV_JRQbsac_v_v9n8Y857Lz/view?usp=drivesdk)
- Advanced: [Designing Data-Intensive Applications, 2nd Ed.](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/)


### Learning Resources
- [DataTalks.Club Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) — best free DE course
- [Data Engineering Course for Beginners](https://www.youtube.com/watch?v=PHsC_t0j1dU)

### 1. SQL & Databases (Foundation)
- [SQL W3School](https://www.w3schools.com/sql/default.asp), [SQL Full Course Youtube for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus&t=1287s), [SQl with AI Datacamp Sheet](./introduction-to-sql-with-ai.pdf)
- Relational Databases: [PostgreSQL W3School](https://www.w3schools.com/postgresql/index.php), [MySQL W3School](https://www.w3schools.com/mysql/default.asp), SQL Server
- [NoSQL (Irrelational Databases)](https://app.datacamp.com/learn/courses/introduction-to-nosql): [MongoDB W3School (document)](https://www.w3schools.com/mongodb/index.php), [Redis Youtube (cache)](https://www.youtube.com/watch?v=XCsS_NVAa1g), InfluxDB (time-series)
- Analytical: BigQuery, Snowflake, Azure Synapse, DuckDB
- Vector DBs: Weaviate, Pinecone (needed for RAG systems)
- DB Client: DBeaver, Datagrip

### 2. [Python for Data Engineering W3School](https://www.w3schools.com/python/default.asp)
- File formats: CSV, JSON, Parquet, Avro, Delta
- Data wrangling with Pandas, PySpark, [Data Wrangling DataCamp Cheat Sheet](./Data_Wrangling_Cheat_Sheet.pdf)
- API consumption and web scraping
- Scheduling and automation with Python scripts
- [Python Full Course for Beginners (13 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=Rq5gJVxz55Q&list=PLNcg_FV9n7qZGfFl2ANI_zISzNp257Lwn)

### 3. ETL / ELT Pipelines
- ETL vs ELT — when to transform before vs after loading
- Batch pipelines: extract → transform → load patterns
- Data modeling: Star Schema, Snowflake Schema, OBT
- [dbt Core](https://github.com/dbt-labs/dbt-core) for SQL-based transformation layers, [dbt Fundamentals](https://courses.getdbt.com/courses/fundamentals)
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
- [Azure DataCampp Course](https://app.datacamp.com/learn/skill-tracks/microsoft-azure-fundamentals-az-900): Data Lake Storage (ADLS), Data Factory (ADF), Synapse Analytics, [Azure CLI DataCamp Cheat Sheet](./Azure_CLI_Cheat_Sheet.pdf)
- [GCP Data Eng. DataCamp Course](https://app.datacamp.com/learn/skill-tracks/google-cloud-data-engineer): BigQuery, Cloud Storage, Dataflow, Pub/Sub, Vertex AI [Google Cloud Associate Engineer freecodecamp youtube Course](https://www.youtube.com/watch?v=OlAmyf8_4O4)
- [Databricks](https://www.youtube.com/watch?v=oA90QLr_PsM&list=PLNcg_FV9n7qZWchr-GE5iPPBmOjiffK6O): Delta Lake, Spark compute, Unity Catalog, [Databricks Academy](https://www.databricks.com/learn/training/home)
- [GitHub Actions DataCamp](https://campus.datacamp.com/courses/cicd-for-machine-learning/introduction-to-continuous-integrationcontinuous-delivery-and-yaml?ex=7): CI/CD for data pipelines
- [AWS DataCamp Course](https://app.datacamp.com/learn/skill-tracks/aws-cloud-practitioner-clf-c02)

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
