Simultaneous Viewing Limit System

A distributed microservices system to enforce simultaneous OTT streaming limits using Spring Boot, Apache Kafka, and Redis.

🚀 Overview

Many OTT platforms face account sharing issues where multiple users stream simultaneously from the same account.

This project implements a scalable, event-driven system that:

Restricts simultaneous streaming per account

Uses asynchronous communication

Handles high concurrency

Ensures low-latency session validation

🏗 Architecture

Services:

Push Service – Handles streaming start/stop events

Check Service – Validates active sessions

Redis Cluster – Fast in-memory session tracking

Kafka Cluster – Asynchronous event communication

