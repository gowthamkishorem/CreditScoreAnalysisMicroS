# Credit Score Analysis Tool (Microservice)

## Overview
A microservices-based backend system developed for automating credit score evaluations. The platform integrates data from financial institutions and credit bureaus to provide real-time credit scoring and predictive analytics for banking personnel.

## Tech Stack
- Java 8+, Spring Boot, Spring Security, Hibernate
- Apache Kafka, Redis
- MySQL (with plans for MongoDB migration)
- Jenkins, Docker, Kubernetes, GitLab
- API Gateway: Spring Cloud Gateway / APIGEE
- Log Management: Log4j2, Splunk

## Setup
```bash
git clone https://github.com/gowthamkishorem/CreditScoreAnalysisMicroS.git
cd CreditScoreAnalysisMicroS
mvn clean install
mvn spring-boot:run
