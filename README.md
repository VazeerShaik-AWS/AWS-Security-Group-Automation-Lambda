# Automated Security Group Automation Updates using AWS Lambda 

## Overview

Designed an automated solution to dynamically update Security Group rules based on changing AWS CloudFront IP ranges using AWS Lambda and SNS, ensuring continuous secure access without manual intervention.

## Objective

* Automatically update Security Groups when CloudFront IP ranges change
* Eliminate manual security rule maintenance
* Ensure uninterrupted and secure access to applications
* Maintain compliance with dynamic AWS infrastructure changes

## Problem Statement

* AWS CloudFront IP ranges change frequently
* Manual updates to Security Groups are error-prone and time-consuming
* Delayed updates can lead to security risks or service disruptions

## Architecture

* Amazon SNS triggers AWS Lambda on IP range update events
* Lambda function fetches the latest AWS IP ranges dynamically
* Security Group rules are updated programmatically
* Logic implemented to handle AWS Security Group rule limits efficiently

## AWS Services Used

* AWS Lambda
* Amazon SNS
* Amazon EC2 (Security Groups)
* AWS Identity and Access Management (IAM)
* Amazon VPC

## Outcome / Business Impact

* Eliminated manual intervention through full automation
* Ensured continuous compliance with updated IP ranges
* Reduced risk of misconfiguration and downtime
* Demonstrated real-world production-grade cloud automation

## Author

**Vazeer Shaik**

AWS Cloud Engineer

---

This project demonstrates hands-on expertise in cloud automation, security and event-driven architecture using AWS.
