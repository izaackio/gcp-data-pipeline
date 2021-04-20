# gcp-data-pipeline

# About
This is an example of building a simple Data pipeline for an ELT-flow within Google Cloud Platform (GCP). The architecture is built upon GCP-services together with dbt. Everything is written in Python. This project is for educational purposes but feel free to utilize any code you might find useful. Inspiration from https://github.com/renatootescu/ETL-pipeline.

# Architecture
- Google Cloud Storage
- Dataflow
- BigQuery
- dbt
- Notebooks

# Data Sourcing and Ingestion
For the purpose of this project we will utilize data from the game "Dota 2". The data can be retrieved via an API available at ...
The data is formatted in json (?).
The data will be ingested via Cloud Dataflow (?) at a certain interval and stored in BigQuery for further processing.
