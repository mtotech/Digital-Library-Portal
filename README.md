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

![](screenshots/cloudDistribution.png)

![](screenshots/cloudwatch_logs.png)

![](screenshots/dynamoDB.png)

![](screenshots/HomePage.png)

![](screenshots/IAM_POLICY.png)

![](screenshots/IAM_ROLE.png)

![](screenshots/Lambda_function.png)

![](screenshots/Router_53.png)

![](screenshots/S3 Website Hosting.png)

![](screenshots/S3_BUCKET.png)

![](screenshots/SES.png)

![](screenshots/ssl_certificate.png)

![](screenshots/WAF.png)

