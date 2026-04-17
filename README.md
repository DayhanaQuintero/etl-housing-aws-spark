# Real Estate ETL Pipeline — AWS & Apache Spark 🏠

Full ETL pipeline on King County housing dataset
using cloud services and distributed processing.

## Tools
- AWS (S3, Glue, Athena)
- Apache Spark (PySpark)
- SQL
- Looker Studio

## Process
1. Dataset upload (21,613 records) to Amazon S3
2. Automatic cataloging with AWS Glue crawler
3. SQL queries in Athena: market KPIs
4. PySpark processing: aggregations by zipcode
5. Interactive dashboard in Looker Studio

## Results
- Average price: $540,088
- Most expensive zipcode: 98039 (~$2.1M average)
- Most properties: zipcode 98103 (602 houses)
