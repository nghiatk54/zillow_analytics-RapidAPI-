# zillow_analytics-RapidAPI-
End to end data pipline: 
- Zillow RapidAPI (extract) -> S3 Bucket (uploaded trigger) -> Lambda function (copy/load) -> S3 Bucket (loaded) -> Lambda function (transformation/load) -> S3 Bucket (load) -> Amazon Redshift
- Công nghệ sử dụng: Python, Apache Airflow, Amazon EC2, Amazon S3, Amazon Redshift, AWS Lambda.
