# carsales_repo
This is the repository for a self learning project called 'Car Sales' wherein I have tried to showcase my learning about Azure Data Engineering Services.

Below are the azure services used in this project:

**For Storage**
- Azure Data Lake Gen2 (Files stored in parquet format)
- Azure Delta Lake (Data stored in Delta format)

**Data Ingestion**
- Azure Data factory (For reading data from the source and dumping it into bronze layer(Azure Data Lake))

**Data Processing**
- Azure Databricks with unity catalog (For processing and cleaning data while it moves from bronze layer upto gold layer)

**Job Orchestration**
- Azure Data Factory Data Pipeline


### Architecure Diagram

![Architecture](./carsales_lakehouse.png)



