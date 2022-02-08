# Ingesting Data Super Heroes Dataset

I used Amazon S3 Bucket, Amazon Redshift and Amazon Athena. Send get files. Store files. 

## Work Flow

![ingesting_data](https://user-images.githubusercontent.com/42489236/151793739-2837bbac-5d43-48b4-bd6a-dd31278d655d.jpg)

## Project Steps

Most of the project i used boto3. Some include AWS Management Console Applications.

1-Create a bucket and send files to the S3 bucket.

2-Create database and table on Amazon Athena. And insert the dataframe in S3 bucket to the table in Amazon Athena. Implement some queries in Athena.

3-Database and table automatically created in AWS Glue Data Catalog after we create them in Amazon Athena. I examined them using boto3.

4-Created parquet-based table.

5-Query data in S3 using Amazon Redshift.(Create schemas, tables etc.)

6-Get dbs from s3 with help of Glue Data Catalog and create tables from zero using Amazon Redshift.
