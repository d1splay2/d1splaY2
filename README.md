Hi i'm Egor, i do mostly data related stuff. All contacts can be found in Github bio

# Projects

This just small descriptions of a projects and tools that used in this projects. Full description, preview, architecture, decision making and steps to reproducement is accessible by clicking on the name of a project or in [Repositories](https://github.com/d1splay2?tab=repositories) tab

## [Spark-On-Demand](https://github.com/d1splay2/Spark-On-Demand)

Scheduled job on Airflow spawn Spark Job on Kuberentes Cluster, read and transform different formats of data in 1 unified format and ensure consistency of data get uploaded in other S3 object storage. In the process of transforming data all logs get sinked, both stdout and Spark Structured logs from all elapsed jobs and can be accessed with Spark History Server that pointed to all logs.

* [Kubernetes (Kind)](https://kind.sigs.k8s.io) - local K8s cluster
* [RustFS](https://github.com/rustfs/rustfs) - S3-compatible object storage
* [Apache Spark](https://github.com/apache/spark) - distributed data processing
* [Spark Operator](https://github.com/kubeflow/spark-operator) - manage Spark apps on K8s
* [Apache Airflow](https://github.com/apache/airflow) - workflow orchestration
* [Delta Lake](https://github.com/delta-io/delta) - storage framework
* [Polars](https://github.com/pola-rs/polars) - lightweight data transformation
* [Fluent Bit](https://github.com/fluent/fluent-bit) - log shipping
* [Helm](https://helm.sh) - K8s package manager

## [Steam-Reviews-Ingestion](https://github.com/d1splay2/Steam-Reviews-Ingestion)

Data comes from users (API's) get transformed, stored and becomes accessible in real-time for BI users in sub-seconds delay

### Tools

* [Kafka](https://github.com/apache/kafka) - message broker
* [Arroyo](https://github.com/ArroyoSystems/arroyo) - streaming
* [Polars](https://github.com/pola-rs/polars) - inital batch
* [RustFS](https://github.com/rustfs/rustfs) - all data object storage
* [Clickhouse](https://github.com/ClickHouse/ClickHouse) - low latency storage
* [Delta Lake](https://github.com/delta-io/delta) - storage framework
* [Metabase](https://github.com/metabase/metabase) - visualization
* [Docker](https://www.docker.com) - containerization
* Makefile - simple orchestration

## [Live-Website-Backend-Storage](https://github.com/d1splay2/Live-Website-Backend-Storage)

From users (API's) data get pushed to message broker, transformed in micro batches and stored in NoSQL database. Also it become accessible for website users to interact in 5-10 seconds delay

* [Apache Spark (Streaming)](https://spark.apache.org/docs/latest/streaming-programming-guide.html) - micro-batch streaming
* [MongoDB](https://github.com/mongodb/mongo) - NoSQL storage
* [Kafka](https://github.com/apache/kafka) - message broker
* [Flask](https://github.com/pallets/flask/) - web-framework
* [Python](https://github.com/python/cpython) - glueing all pieces and writing logic
* [Docker](https://www.docker.com) - containerization
