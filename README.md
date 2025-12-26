# Midas – Transaction Processing System

## Overview
Midas is a backend transaction processing system inspired by real-world financial services workflows. 
The system handles transaction requests through REST APIs, streams events using Apache Kafka, 
and persists processed data into a SQL database.

## Tech Stack
- Java
- Spring Boot
- Apache Kafka
- SQL
- REST APIs
- Maven

## Architecture Flow
1. Client sends a transaction request via REST API
2. Transaction event is published to a Kafka topic
3. Kafka consumer processes the transaction asynchronously
4. Final transaction details are stored in the database

## Key Concepts Implemented
- Event-driven architecture
- Producer–Consumer messaging pattern
- RESTful backend service design
- Database persistence
- Layered Spring Boot architecture

## Learning Outcomes
- Understanding backend workflows used in financial systems
- Hands-on experience with Kafka-based messaging
- Designing scalable backend services
- Writing clean, production-style Java code

## Disclaimer
This project was developed as part of the JPMorgan Chase Software Engineering Job Simulation on the Forage platform and is intended for educational purposes.


## Author
Priyanka Kumari Pandey  
Aspiring Backend / Software Engineer

