Multi-Tier Kubernetes Demo: Product Service + PostgreSQL
A minimal but realistic two-tier system:

Service tier — Spring Boot REST API (product-service) exposing /api/products
Database tier — PostgreSQL, seeded with sample data on first boot
The service tier fetches rows from the database tier over JDBC, through a Kubernetes-internal DNS name (postgres-service), and exposes that data externally over HTTP.

Prerequisites
--------------------
Docker
A Kubernetes cluster
kubectl configured 

Application End Point: http://136.68.43.201/api/products

Code Repository Link: https://github.com/vaishalichauhan/assignment

Docker URL: https://hub.docker.com/u/23451
