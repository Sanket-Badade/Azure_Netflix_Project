# Netflix-end-to-end-data-pipeline 


##This project demonstrates a simple end-to-end data pipeline built using PySpark and Azure Data Lake. The pipeline processes Netflix dataset using Medallion Architecture (Bronze, Silver, Gold layers) to transform raw data into meaningful insights.


## Architecture

<img width="1502" height="688" alt="IMG_20260325_101754" src="https://github.com/user-attachments/assets/0d9ca795-d901-4c23-96f0-5f0880774a47" />
   

## Tech Stack

- PySpark
- Azure Data Lake Storage (ADLS)
- Databricks (for processing)
- Power BI (for visualization)


## Project Workflow

1. Load Netflix dataset (CSV/JSON)
2. Ingest data into Bronze layer using ADF Pipeline (raw storage)
3. Clean and transform data using PySpark (Silver layer)
4. Perform aggregations (Gold layer)
5. Visualize data using Power BI


⭐ This project is built for learning and demonstrating data engineering concepts using a real-world dataset.

