# API Gateway

Dockerfile for API gateway image.

# Configuration

## Basic
- `secret`: `f35cb63ee4d0405ad9f009e998532d21208d31b3`
- `listen_port`: 8080
- `redis`: looks for redins on `api-gateway-redis` host, on default
  6379 port

## Analytics

Analytics enabled. Expecting Mongo DB on `api-gateway-mongo` host.
