# Kavali Yashwanth Royal

Data engineer in India. I build pipelines that land messy data, test it, and
refuse to publish a number that fails a check — Python, SQL, PySpark, dbt, Kafka
and AWS.

Right now I am working the stack end to end: batch on AWS, streaming with Kafka
and Spark, and the dbt transformation layer on top. Four projects, each runnable
from a clone, each with the tests and the numbers to back it up.

## Pinned work

| Project | What it demonstrates |
|---|---|
| **[aws-retail-data-platform](https://github.com/Yashu24-coder/aws-retail-data-platform)** | Batch ELT on AWS — S3 medallion layers, Glue PySpark, Athena and Redshift Serverless, 12 data-quality gates, 23 tests, everything in Terraform |
| **[streaming-orders-pipeline](https://github.com/Yashu24-coder/streaming-orders-pipeline)** | Kafka to Spark Structured Streaming — 120s watermark, 5-minute tumbling windows, exactly-once sink, dead-letter queue with reason codes |
| **[dbt-saas-analytics](https://github.com/Yashu24-coder/dbt-saas-analytics)** | dbt analytics engineering — 13 models, 27 data tests, incremental MRR fact table, SCD2 snapshot, cohort retention that reconciles with revenue |
| **[aws-nyc-taxi-data-engineering](https://github.com/Yashu24-coder/aws-nyc-taxi-data-engineering)** | NYC TLC lakehouse — S3 bronze/silver/gold, Glue, Athena and Terraform |

## How to read these

Every repository has a **"What this project does not do"** section. Start there.
It says which parts run in CI and which need Docker or an AWS account, and it
says plainly that the data is synthetic or public. I would rather you knew the
edges than found them.

## Tools

`Python` `SQL` `PySpark` `dbt` `Kafka` `AWS (S3, Glue, Athena, Redshift)`
`Terraform` `Docker` `DuckDB` `pytest` `GitHub Actions`

## Contact

- Email: 176301502+Yashu24-coder@users.noreply.github.com
- GitHub: [@Yashu24-coder](https://github.com/Yashu24-coder)
