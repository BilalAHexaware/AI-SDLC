# Non-Functional Requirements

## Performance
Response time < 200ms (p95); support 100 concurrent requests.

## Reliability
Availability 99.5% uptime SLA; graceful error handling on database failure.

## Scalability
Stateless design; HikariCP connection pooling; horizontal scaling support.
