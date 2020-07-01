# Web-Log-Analysis-using-AWS
This project was completed to expound upon the concepts learned in the course - Data Analysis Fundamentals by AWS.


Amazon Kinesis Analytics is a very convenient way to process streaming data in real time with Standard SQL. It enables creating and executing SQL queries on real-time, incoming streaming data so as to gain actionable insights and respond to business needs promptly. 

In the tasks completed as part of this tutorial, I learnt how to ingest streaming log data, aggregate that stream data and persist the aggregated data so that same can be analyzed and visualized. Here I have created a complete end-to-end system that integrates several AWS services. I have analyzed a live stream of Apache access log data and aggregated the total request for each HTTP response type every minute. To visualize the results in near real-time, I have used a UI Tool, Kibana to chart the results. 

One major benefit of using these AWS services for log analysis, was that the entire analysis infrastructure was created with a serverless architecture. The system was created by integrating Amazon Kinesis Firehose, Amazon Kinesis Analytics, Amazon Elasticsearch Service. The architecture of the solution can be seen below, and the complete project description can be seen in the attached PDF.

![Architecture]()
