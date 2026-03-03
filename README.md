# FlowForge Platform API
![CI](https://github.com/My-second-free-organization/platform-api/actions/workflows/ci.yml/badge.svg)

High-performance API Gateway for FlowForge. REST + GraphQL, JWT auth, rate limiting, circuit breaker.

## Quick Start
```bash
go run ./cmd/platform-api
go test ./...
```

## Env Vars
- `SERVER_PORT` (8080)
- `DATABASE_URL`
- `REDIS_URL`
- `JWT_SECRET`
- `CORE_SERVICE_URL`
