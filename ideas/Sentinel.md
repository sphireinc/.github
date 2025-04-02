# Sentinel – Secure API Gateway & Request Middleware for Go  

## Overview  
Sentinel is a **lightweight API gateway and middleware framework** for Go, designed to provide **rate limiting, authentication, logging, and security enforcement** for APIs. It helps developers protect and optimize their services with minimal overhead.  

## Key Features  

### 🔐 Security & Authentication  
- **JWT, OAuth2, API Key, and HMAC authentication**  
- **IP whitelisting & blacklisting**  
- **Role-based access control (RBAC) and permission enforcement**  

### ⚡ Performance & Rate Limiting  
- **Customizable rate limiting** (token bucket, sliding window, leaky bucket)  
- **Per-user, per-IP, and per-endpoint rate limits**  
- **Automatic request throttling to prevent abuse**  

### 📜 Logging & Monitoring  
- **Real-time API request logging**  
- **Built-in integration with Prometheus, Grafana, and OpenTelemetry**  
- **Request tracing and error analytics**  

### 🔄 Request Transformation & Caching  
- **Modify, enrich, or validate requests before forwarding**  
- **Automatic response caching** for improved performance  
- **Header and query parameter injection** for downstream services  

## Use Cases  
✅ **Protect APIs from abuse, DDoS, and unauthorized access**  
✅ **Centralized authentication & security enforcement** for microservices  
✅ **Monitor and log API traffic for debugging and analytics**  
✅ **Optimize API response times with smart caching**  
✅ **Easily integrate with cloud-native and on-prem API services**  
