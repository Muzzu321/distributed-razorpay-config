# Distributed Payment Gateway

A production-oriented distributed payment gateway inspired by Razorpay/Stripe, built using microservices and event-driven architecture.

## Features

- Supports Card, UPI, Net Banking, and Wallet payments
- Strategy Pattern based payment adapter layer
- SAGA Pattern for distributed transactions
- Transactional Outbox with Kafka for reliable event delivery
- Redis SETNX-based idempotency to prevent duplicate payments
- Resilience4J Circuit Breaker and failure simulation
- AES-256 encrypted card vault
- Webhook delivery with HMAC-SHA256, retries, and DLQ replay
- Spring Batch-based merchant settlement
- Kubernetes HPA for autoscaling
- Prometheus, Grafana, and Zipkin for observability

## Technologies

- Java, Spring Boot, Spring Cloud
- Apache Kafka
- PostgreSQL
- Redis
- Resilience4J
- Docker & Kubernetes
- Prometheus, Grafana & Zipkin
- Apache JMeter

## Architecture

<img width="900" alt="Distributed Payment Gateway Architecture" src="https://github.com/user-attachments/assets/4faabe78-a19f-43ee-a52e-9d71df805288" />


