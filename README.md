# End-to-End Data Engineering Project on AWS

[![AWS CloudFormation](https://img.shields.io/badge/AWS-CloudFormation-FF9900.svg?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/cloudformation/)
[![AWS Glue](https://img.shields.io/badge/AWS-Glue-232F3E.svg?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/glue/)
[![AWS Athena](https://img.shields.io/badge/AWS-Athena-232F3E.svg?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/athena/)
[![AWS QuickSight](https://img.shields.io/badge/AWS-QuickSight-232F3E.svg?style=for-the-badge&logo=amazon-aws)](https://aws.amazon.com/quicksight/)

This project developes a data engineering pipeline on the AWS cloud, including storing, transforming and analysing data. The project utilizes a Spotify data set from 2023 (obtained from https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset and demonstrates various data engineering tasks, including data ingestion, transformation, and visualization.

## Dataset

The project uses the Spotify data set 2023, which includes the following five CSV files:
- `albums.csv`
- `artists.csv`
- `spotify_data.csv`
- `spotify_features.csv`
- `spotify_tracks.csv`

## Project Steps

1. **Create an IAM User**:
    - Set up an IAM user in AWS and assign the relevant role for accessing and managing AWS services.

2. **Create an S3 Bucket**:
    - Create an S3 bucket in AWS and upload the Spotify data set files.

3. **Create a Data Pipeline using AWS Glue**:
    - Use AWS Glue to create a data pipeline that transforms and transfers data from the staging layer to the data warehouse.

4. **Create a Glue Crawler**:
    - Set up a Glue Crawler to scan the data in S3, create a data catalog, and define the database and tables.

5. **Query Data using Athena**:
    - Use Amazon Athena to query the data from the data catalog.

6. **Create Visualizations using Amazon QuickSight**:
    - Use Amazon QuickSight to create visualizations and derive insights from the data.

## Prerequisites

- AWS account
- AWS CLI configured
- IAM role with necessary permissions for S3, Glue, Athena, and QuickSight

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-repo/aws-data-engineering-project.git
    cd aws-data-engineering-project
    ```

2. **Set up AWS environment**:
    - Create an IAM user and assign roles.
    - Create an S3 bucket and upload the dataset files.

3. **AWS Glue Setup**:
    - Create a Glue job for ETL (Extract, Transform, Load) processes.
    - Configure the Glue Crawler to create a data catalog.

4. **Query with Athena**:
    - Use the Athena console to run SQL queries on the data catalog.

5. **Visualize with QuickSight**:
    - Set up Amazon QuickSight and create visualizations based on the processed data.

## Usage

1. **Data Ingestion**:
    - Upload CSV files to the S3 bucket.

2. **Data Transformation**:
    - Use AWS Glue to transform and transfer data.

3. **Data Querying**:
    - Query data using Amazon Athena.

4. **Data Visualization**:
    - Create dashboards and reports using Amazon QuickSight.
