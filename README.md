# AWS-Console-Alerts-Bot

**OBJECTIVE**: Getting Real Time AWS Management Console Alert via Telegram Bot Using AWS Serverless Services.

What is Serverless?

Serverless is a cloud-native development model that refers to serverless applications. Serverless applications are ones that don’t need any server provision and do not require managing servers.

**Services Used for Fabricating:**

1)AWS Lambda

2)AWS Cloud Trail

3)AWS Event Bridge

**Architecture:**

![image](https://user-images.githubusercontent.com/87435344/230758251-e45c21e8-fe24-4e6b-9d0a-98923778bb1a.png)

**Architecture Flow:**

When and User Login to AWS Management Console using root user Credentials, the Real time date Event occurs then lambda function which is integrated with the trail and event bridge got triggered and the user get the alert via telegram bot.  

**Bot Link:** https://t.me/AWSLOGINALERTBOT


