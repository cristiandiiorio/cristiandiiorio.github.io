---
layout: page
title: AWS Blog App Deployment and Testing
description: AWS Blog App Deployment and Testing with JMeter
img: assets/img/cloudcomputing-report-image.png
importance: 1
category: completed
---

Designed and deployed a scalable, fault-tolerant three-tier web application on AWS using Flask for a blog platform supporting image uploads. Implemented a secure multi-AZ infrastructure with EC2 instances managed by an Auto Scaling Group, an Application Load Balancer, and a Multi-AZ RDS PostgreSQL database. Integrated S3 for image storage and set up bastion/tester hosts for secure access and performance evaluation. Developed step-scaling policies based on CloudWatch alarms to dynamically respond to traffic surges. Performance tested with Apache JMeter under heavy and light workloads, achieving zero error rates across millions of transactions and showcasing effective scaling behavior and responsiveness.

Here is the full [report]({{ "/assets/pdf/cloudcomputing-report.pdf" | relative_url }}){:target="_blank"}.