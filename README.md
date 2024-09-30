
## Spark ETL Pipeline for Enrollment Analytics
This project implements a scalable ETL pipeline using Apache Spark to process enrolment data from various cities and states. The goal is to transform, filter, and aggregate the data to derive key insights, such as total enrolments by state and city, over a 10-year period.

## Key Features:
Total Enrolments by State in 2021: Calculates the total enrolments per state in the year 2021.
Top-10 Cities with the Most Enrolments: Identifies the top-10 cities with the highest enrolments in 2021.
Enrolments Over a 10-Year Period: Aggregates total enrolments at both state and city levels for a custom 10-year period.
Data Imputation & Deduplication: Handles missing enrolment dates and removes duplicate student enrolments.
Steps:
1. Data Ingestion: Reads and processes CSV data with Spark.
2. Transformation: Filters and aggregates data for analytical queries.
3. Relational Database Schema: Stores processed data in a relational database (Postgres/SQL).
4. Analytics Queries: Executes Spark SQL queries to answer analytical questions.
## Tech Stack:
1. Apache Spark (Data Processing & Analytics)
2. Postgres/SQL (Relational Database)
3. Python (ETL Pipeline Development)


## Setup
1. Clone the repository.
2. Navigate to the project directory.
3. Create a virtual environment (optional but recommended).
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   