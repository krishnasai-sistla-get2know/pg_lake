# pg_lake

### 📦 pg_lake: Postgres with Iceberg and data lake access – Docker Images
This repository provides a Dockerized version of the pg_lake and pgduck-server. It is not part of the Apache Iceberg project i.e., `UNOFFICIAL` hence, use it at your own risk. It simplifies deployment of the Iceberg catalog by packaging it into a ready-to-use Docker image, suitable for development, testing, or production environments.

✨ Features
Prebuilt Docker image of pg_lake and pgduck-server

Easily configurable via environment variables

Ready for integration with Iceberg clients (e.g., Spark, Flink, Trino, DuckDB)

Compatible with MinIO, AWS S3, Nessie, and other Iceberg-compatible backends

Lightweight and minimal base image

### 🚀 Getting Started
```bash
docker run -p 8181:8181 ghcr.io/krishnasai-sistla-get2know/pg_lake-postgres:latest
docker run -p 8181:8181 ghcr.io/krishnasai-sistla-get2know/pgduck-server:latest
```

### 📝 License
This project packages and redistributes software licensed under the Apache License 2.0. See [NOTICE](./NOTICE) and [LICENSE](./LICENSE) for details.
