Hi i'm Egor, i do mostly data related stuff. All contacts can be found in Github bio

# Projects

This just small descriptions of a projects and tools that used in this projects. Full description, preview, architecture, decision making and steps to reproducement is accessible by clicking on the name of a project or in [Repositories](https://github.com/d1splay2?tab=repositories) tab

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
* [Flask](https://github.com/pallets/flask/) - web-framework
* [Python](https://github.com/python/cpython) - glueing all pieces and writing logic
* [Docker](https://www.docker.com) - containerization

# WIP Projects

