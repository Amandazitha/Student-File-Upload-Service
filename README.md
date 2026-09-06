# Cloud-Based Student File Upload and Submission Service

## Project Description

This project is a cloud-based service that allows students to submit files electronically.

## How It Works

1. The student selects a file.
2. The upload endpoint receives the submission.
3. AWS Lambda validates and processes the submission.
4. Submission information is stored in DynamoDB.
5. CloudWatch records system logs.
6. The student receives a submission ID and status.

## Project Scope

The project focuses on one student file submission process using synthetic test data.

## Technology

* AWS Lambda
* DynamoDB
* CloudWatch
* Upload Endpoint

## Repository Structure

* `documentation/` – project documents and decisions
* `architecture/` – architecture diagrams
* `evidence/` – testing and milestone evidence

## Team

This project is developed as a group practical for 4CPS501B.
