# ADR-001: Platform Route

## Decision

Our group chose AWS as the preferred platform for the Student File Upload Service.

## Alternative

Our alternative is SAM Local.

## Why we chose AWS

- AWS provides the cloud services needed for our project.
- AWS Lambda can process the file submission.
- DynamoDB can store submission information.
- CloudWatch can record system logs.

## Fallback

If we have problems accessing AWS, we will use SAM Local to test the service locally.

## Risks

- AWS setup may be difficult.
- Incorrect configuration may delay the project.
- Cloud resources may create costs if they are not monitored.

## Cost Control

We will monitor resource usage and avoid unnecessary cloud resources.

## Final Decision

AWS is our preferred platform, with SAM Local as the fallback.
