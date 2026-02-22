# 🚀 GCP Services for Data Engineering with Projects

Welcome to the comprehensive repository for **GCP Services for Data Engineering with Projects**. This course is designed to take you from a beginner to an advanced level in Google Cloud Platform (GCP) data engineering, covering everything from fundamental services to building complex, industrial-scale data pipelines.

---

## 🛠️ Tech Stack & Tools

### 🌩️ Cloud Platform & Core Services
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Google Cloud Storage](https://img.shields.io/badge/GCS-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![GCP Pub/Sub](https://img.shields.io/badge/Pub/Sub-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

### 📊 Big Data & Analytics
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Dataproc](https://img.shields.io/badge/Dataproc-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Dataflow](https://img.shields.io/badge/Dataflow-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![BigTable](https://img.shields.io/badge/BigTable-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)

### ⚙️ Processing & Orchestration
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Apache Beam](https://img.shields.io/badge/Apache_Beam-FF5722?style=for-the-badge&logo=apache-beam&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-00AEEF?style=for-the-badge&logo=apache&logoColor=white)
![Apache Hive](https://img.shields.io/badge/Apache_Hive-FDE12D?style=for-the-badge&logo=apache-hive&logoColor=black)

### 💻 Infrastructure & Serverless
![Cloud Run Functions](https://img.shields.io/badge/Cloud_Run_Functions-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Compute Engine](https://img.shields.io/badge/Compute_Engine-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### 🐍 Languages & Libraries
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

### 🚀 CI/CD & Others
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Cloud Build](https://img.shields.io/badge/Cloud_Build-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Secret Manager](https://img.shields.io/badge/Secret_Manager-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

---

## 📚 Course Modules

### 🔹 Module 1: GCP Foundations & Serverless
- **Fundamentals**: GCS (Google Cloud Storage), IAM (Identity and Access Management).
- **Compute**: GCP Compute Engine, Cloud Monitoring & Logging.
- **Serverless**: GCP Cloud Run Functions, Cloud Build.
- **Messaging & Orchestration**: GCP Pub-Sub, Cloud Scheduler.
- **Key Labs**:
  - GCS Bucket management via CLI & Python.
  - Setting up Compute Engines and monitoring health.
  - Implementing HTTP & Event-driven Cloud Run Functions.
  - CI/CD with Cloud Build & GitHub.

### 🔹 Module 2: Databases, Streaming & BigQuery
- **Storage & DB**: Cloud SQL (MySQL), Secret Manager, BigTable.
- **Data Processing**: GCP Dataflow, Apache Beam (Batch & Streaming).
- **Analytics**: BigQuery Architecture (Capacitor, Colossus, Dremel).
- **Modern Architecture**: Medallion Architecture (Bronze, Silver, Gold layers).
- **Key Labs**:
  - CDC (Change Data Capture) streams from BigTable to Pub-Sub.
  - Dataflow FlexTemplates for custom pipelines.
  - Advanced BigQuery operations: Partitioning, Clustering, Time Travel.
  - Geolocation & AI-assisted analysis with Gemini.

### 🔹 Module 3: Big Data Processing & Orchestration
- **Managed Clusters**: GCP Dataproc (Hadoop, Yarn, Spark, Hive).
- **Serverless Spark**: Dataproc Serverless.
- **Orchestration**: GCP Composer (Managed Apache Airflow).
- **Key Labs**:
  - Incremental data ingestion (SCD Type 2) in BigQuery.
  - Spark Structured Streaming with Iceberg on GCS.
  - Designing complex Airflow DAGs for automated workflows.

### 🔹 Module 4: No-Code Pipelines & Workflows
- **ETL/ELT**: GCP Data Fusion (Wrangler Transformations).
- **Orchestration**: GCP Workflows.
- **Key Labs**:
  - Building no-code pipelines for Fintech & HackerNews data.
  - Orchestrating Cloud Run Functions & Dataproc jobs using GCP Workflows.
  - Handling event-driven triggers for SCD2 operations.

---

## 🏗️ Industrial Projects

This repository includes several end-to-end industrial projects:

| # | Project Name | Tech Stack |
|---|--------------|------------|
| 1 | **✈️ Flight Booking Data Pipeline** | Airflow, PySpark, Dataproc Serverless, BigQuery, CI/CD with GitHub Actions |
| 2 | **🌦️ Weather Forecast Data Processing** | Open Weather API, Composer, PySpark, Dataproc Serverless, BigQuery |
| 3 | **🚗 Uber Car Idle Realtime Alerts** | Pub-Sub, Dataflow (Apache Beam), BigQuery, Cloud Run Functions |
| 4 | **💳 Credit Card Fraud Alert Pipeline** | Airflow, Dataproc Serverless, Python, BigQuery, PyTest, Looker Studio |
| 5 | **🏆 Realtime Game Leaderboard** | Pub-Sub, Dataflow, BigQuery, Cloud Run Functions, Scheduled Queries |
| 6 | **📺 YouTube Wide Trending Engagement** | GCS, Composer, PySpark, Dataproc, Iceberg, BigQuery |

---

## 🚀 Getting Started

1.  **GCP Account**: Set up a [GCP Free Tier Account](https://cloud.google.com/free).
2.  **SDK**: Install and initialize the [Google Cloud SDK](https://cloud.google.com/sdk/docs/install).
3.  **Python**: Ensure Python 3.9+ is installed.
4.  **Clone the Repo**:
    ```bash
    git clone https://github.com/Ratnesh-181998/GCP-Data-Engineering.git
    cd GCP-Data-Engineering
    ```

---

## 🤝 Contributing
Contributions are welcome! If you find a bug or have a suggestion, please open an issue or a pull request.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
**Happy Cloud Engineering!** ☁️⚓
