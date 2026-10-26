# Cloud-Computing-TA_2
template.yaml – A fully functional AWS CloudFormation template written in YAML that automates the deployment and configuration of AWS resources, including S3, Lambda, VPC, and SNS. It defines the infrastructure, configures S3 event triggers, and enables automated email notifications through SNS.

AWS Serverless Event-Driven Architecture using CloudFormation

This project implements an event-driven, serverless architecture on AWS using AWS CloudFormation, Amazon S3, AWS Lambda, Amazon VPC, and Amazon SNS. When a file is uploaded to an S3 bucket, an event trigger invokes a Lambda function, which processes the event and sends an email notification through SNS. The infrastructure is provisioned using Infrastructure as Code (IaC) with a reusable YAML-based CloudFormation template.

Key Features

Infrastructure as Code: Automated AWS resource provisioning using template.yaml.

S3 Event Trigger: Automatically detects file uploads to an S3 bucket.

AWS Lambda: Executes serverless logic in response to S3 events.

VPC Integration: Demonstrates the network architecture and configuration for the Lambda execution environment.

SNS Notifications: Sends email notifications when the event-processing workflow is triggered.

Architecture Diagram: Visual representation of the AWS components and event flow.

Execution Report: Screenshots documenting successful stack creation, S3 file uploads, Lambda execution, and SNS email notifications.

Repository Contents

template.yaml — AWS CloudFormation template.
