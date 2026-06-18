# -multi-region-dr-architecture
# PaySecure Multi-Region Disaster Recovery Architecture

## Project Overview

This project proposes a Multi-Region Disaster Recovery (DR) Architecture for PaySecure Gateway using Amazon Web Services (AWS). The solution is designed to ensure high availability, business continuity, and minimal downtime during regional failures.

## Objectives

* Design a highly available disaster recovery architecture.
* Achieve RPO of less than 1 minute.
* Achieve RTO of less than 5 minutes.
* Ensure secure and reliable payment processing.
* Support regulatory compliance and business continuity.

## AWS Services Used

* Amazon Route 53
* Application Load Balancer (ALB)
* Amazon EKS / EC2
* Amazon Aurora PostgreSQL
* Amazon DynamoDB Global Tables
* Amazon ElastiCache Redis
* Apache Kafka

## Architecture

The architecture uses AWS Mumbai Region as the Primary Region and AWS Hyderabad Region as the Disaster Recovery Region with continuous cross-region replication and automatic DNS failover.

## Key Features

* Multi-Region Disaster Recovery
* Active-Passive Deployment Strategy
* Automatic DNS Failover
* Cross-Region Database Replication
* High Availability
* Business Continuity

## Technologies

* AWS Cloud
* Disaster Recovery
* Cloud Architecture
* High Availability
* DevOps Concepts

## Author

Trusha Manwar
BCS Student
