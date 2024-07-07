## Introduction

AWS CloudTrail is a vital service for anyone using Amazon Web Services (AWS). It provides comprehensive logging and monitoring capabilities, enabling users to track and record API calls and account activity. AWS CloudTrail and CloudWatch to help you understand their unique benefits and use cases.

## **What is AWS CloudTrail?**

AWS CloudTrail is a service that enables governance, compliance, and operational and risk auditing of your AWS account. With CloudTrail you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services.

## CloudTrail provides three ways to record events

### **Event history** –

The **Event history** provides a viewable, searchable, downloadable, and immutable record of the past 90 days of management events in an AWS Region. You can search events by filtering on a single attribute. You automatically have access to the **Event history** when you create your account. 

### **CloudTrail Lake** –

AWS CloudTrail Lake is a managed data lake for capturing, storing, accessing, and analyzing user and API activity on AWS for audit and security purposes. CloudTrail Lake converts existing events in row-based JSON format to Apache ORC format

### **Trails** –

*Trails* capture a record of AWS activities, delivering and storing these events in an Amazon S3 bucket, with optional delivery to CloudWatch and AmazonEventBridge. You can input these events into your security monitoring solutions. You can also use your own third-party solutions or solutions such as Amazon Athena to search and analyze your CloudTrail logs. You can create trails for a single AWS account or for multiple AWS accounts by using AWS Organizations.