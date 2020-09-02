# serverless-aws-udemy
Lessons learned from "aws-serverless-a-complete-introduction" course

S3 => https://aws.amazon.com/s3/?nc2=h_m1

API Gateway => https://aws.amazon.com/api-gateway/?nc2=h_m1

Lambda => https://aws.amazon.com/lambda/?nc2=h_m1

DynamoDB => https://aws.amazon.com/dynamodb/?nc2=h_m1

Cognito => https://aws.amazon.com/cognito/?nc2=h_m1

Route 53 => https://aws.amazon.com/route53/?nc2=h_m1

CloudFront => https://aws.amazon.com/cloudfront/?nc2=h_m1

# API Gateway: Useful Resources & Links
We're going to dive into API Gateway together, no worries. But it's never too early to share some useful links.

If you want to follow along or dive deeper into AWS API Gateway after finishing this section, the following two links will be very helpful:

- API Gateway Overview: https://aws.amazon.com/api-gateway/

- API Gateway Developer Documentation: https://aws.amazon.com/documentation/apigateway/

Understanding the costs of API Gateway is also crucial. What you see in this course will be within the free tier but once you start playing around with it on your own or you're using it for production, you may encounter costs.

Check the following link to understand what's free and what's not: https://aws.amazon.com/api-gateway/pricing/

# Understanding AWS Permissions (IAM)
Feel free to skip this article if you're already aware about how AWS Security Model and IAM (Identity and Access Management) works.

I strongly recommend watching this video to get a brief overview: https://youtu.be/9CKsX6MOPDQ

Besides that, have a look at the following article to get an introduction: http://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

By default, AWS doesn't give any permissions to any of your services. That means, that no service may interact with other services.
