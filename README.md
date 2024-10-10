# spotify-trends-end-to-end-dataengineering-pipeline
In this project, we will create an ETL pipeline utilizing the Spotify API on AWS. The pipeline will extract data from the Spotify API, transform it into a different format, and load it into an AWS data store.

## Objective
This project aims to develop a robust data pipeline for extracting, transforming, and analyzing Spotify data using various AWS services. The pipeline will connect to the Spotify API to fetch relevant data and store it systematically in AWS S3. The extraction process will be automated by deploying code on AWS Lambda, which will run at scheduled intervals or trigger events.

Once the data is extracted, a transformation function will be implemented to clean and format the data for further analysis. This function will be designed to perform various data processing tasks, such as normalization, aggregation, and filtering, based on specific requirements.

To enhance the pipeline's efficiency and reliability, an automated trigger will be established to monitor changes or updates in the extracted data, executing the transformation function as needed.

The transformed data will be stored back in AWS S3, ensuring proper organization and structure for easy access and retrieval for further analysis.

Additionally, the project will involve creating analytics tables using AWS Glue and Athena. These services will help define the data schema and enable efficient querying and analysis of the transformed data.

By implementing this Spotify data pipeline on AWS, the project aims to deliver a scalable, reliable, and automated solution for extracting, transforming, and analyzing Spotify data, thereby unlocking valuable insights for various analytical purposes.


## Architecture

![Screenshot 2024-10-10 101543](https://github.com/user-attachments/assets/6f50190f-2a38-460a-afeb-f1b409015353)


## Tools & Services

Spotify API
AWS Lambda
AWS S3 (Simple Storage Service)
AWS Glue
Amazon Athena


