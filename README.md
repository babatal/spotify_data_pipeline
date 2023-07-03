# Spotify Data Engineering Data Pipeline Project

The data pipeline will be implemented in the following stages:

1. Data Extraction: Integrating with the Spotify API to extract data about songs, artists, playlists, and other relevant information.

2. AWS Lambda Deployment: deploy the data extraction code on AWS Lambda, which runs the extraction process automatically and at scheduled intervals.

3. Data Transformation: Writing a transformation function to process the raw data into a structured format suitable for analytics.

4. Automated Trigger: Building an automated trigger on the transformation function to run it automatically whenever new data is extracted.

5. Data Storage: Storing the transformed data files properly in an AWS S3 bucket.

6. Building Analytics Tables: Using AWS Glue, analytics tables created on top of the data stored in S3, making it easy to query and analyze the data using AWS Athena.
