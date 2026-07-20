# Digital-Library-Portal
A production-style serverless web application deployed on AWS to demonstrate secure content delivery, training registration, digital library management, enquiry submission, email notification, and cloud-native serverless architecture.
## Features
This portal will provide: 

•	Digital Library 

•	Publication Catalogue 

•	Research Repository 

•	Training Material Request 

<img width="940" height="402" alt="image" src="https://github.com/user-attachments/assets/789919a1-3bec-48e4-b939-89ae56d24dbc" />

## AWS Architecture
Internet Users

       │
       
Route53

       │
       
CloudFront (HTTPS)

       │
       
Amazon S3 Static Website

       │
       
────────────────────────────────

       │
       
API Gateway

       │
       
Lambda

       │
       
 ├───────────────┐
 
 │               │
 
SES          DynamoDB

 │               │
 
Notification Contact /
Emails         

CloudWatch

Monitoring + Logs

![](screenshots/api_gateway.png)

