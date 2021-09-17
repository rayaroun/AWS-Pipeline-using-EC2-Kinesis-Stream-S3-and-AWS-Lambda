## Learning AWS tools

I am using this repository to store my notes about various AWS services that I have learned as well as a complete record of how to build a pipeline using the tools mentioned. 

In the pipeline, we build a system that works from end to end. We monitor new information being uploaded into the log directory of the EC2 host. The kinesis stream picks that data up. AWS Lambda inserts that data into a DynamoDB table. We can now imagine a mobile application that talks directly to the DynamoDB instance and returns the information.

The pipeline file : Pipeline building manual.


The notes created by me consist of : 
* AWS Lambda
* AWS Kinesis
* AWS S3
* DynamoDB
* AWS Glue
* AWS EMR 