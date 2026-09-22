# EMK LINKS ART GALLERY — Marketing Intelligence Platform

Production-oriented starter architecture for a real-time marketing intelligence platform.

## Core architecture
- Streaming: Redpanda/Kafka-compatible event bus
- API: FastAPI
- Analytics: ClickHouse
- Operational data: PostgreSQL
- Connectors: social, web, CRM and campaign event ingestion
- Intelligence: analytics/AI insight layer
- Experience: live dashboards and real-time alerts

## Intended flow
Sources → Connectors → Redpanda/Kafka → Stream processing → ClickHouse/PostgreSQL → Analytics/AI → Dashboards & Alerts

This package is a reconstructed starter scaffold based on the EMK LINKS platform architecture discussed previously.
