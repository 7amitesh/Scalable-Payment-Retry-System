# Fault-Tolerant Payroll Processing System

A backend payroll processing platform designed to ensure reliable salary processing, retry handling, and SLA-safe escalation workflows.



## Tech Stack

- Java
- Spring Boot
- MySQL
- Thymeleaf
- AWS
- Maven


## Key Features

- Automated payroll processing workflows
- Retry handling with exponential backoff
- SLA-based escalation and notification system
- Structured logging and centralized error handling
- Live payroll monitoring dashboard
- Fault-tolerant backend workflow design

---

## System Architecture

```text
Payroll Request
      ↓
Payroll Processing Service
      ↓
Retry Handler & Scheduler
      ↓
SLA Escalation Engine
      ↓
Notification Service
      ↓
Monitoring Dashboard
```


## Project Structure

```text
src/
├── controller/
├── service/
├── scheduler/
├── observer/
├── factory/
├── repository/
├── model/
├── config/
└── exception/
```



## Getting Started

### Clone Repository

```bash
git clone https://github.com/7amitesh/Scalable-Payment-Retry-System.git
```

### Navigate to Project

```bash
cd Scalable-Payment-Retry-System
```

### Run Application

```bash
mvn spring-boot:run
```

### Open Dashboard

```text
http://localhost:8080/dashboard
```


## Core Concepts

- Fault-Tolerant System Design
- Retry Recovery Workflows
- SLA Escalation Handling
- Concurrent Backend Processing
- Structured Logging
- Scheduler-Based Automation


## Future Improvements

- Redis-based retry queue
- Kafka event streaming
- Docker deployment
- Microservices architecture

