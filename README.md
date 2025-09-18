Automated-Lambda-Data-Processing-Pipeline

📌 Project Description

Serverless Lambda Data Processing Pipeline is a cloud-based, event-driven solution built on AWS that demonstrates how to process and transform data automatically without managing servers.

Whenever a CSV file is uploaded to an Amazon S3 bucket, an AWS Lambda function is triggered. The function reads the file, processes the records, and performs salary aggregation by country (India & US). The processed results are then stored in a separate S3 output bucket as a new CSV file.

This project showcases:

1.Serverless Architecture – fully managed, scalable, and cost-efficient.

2.Event-Driven Processing – S3 triggers Lambda instantly on file upload.

3.Data Transformation – aggregates and summarizes salary data.

4.Automation – end-to-end pipeline with zero manual intervention.

