# Grafana LGTM Stack with Docker Compose

Based on the official Grafana LGTM (Loki, Tempo, Mimir) stack, this repository provides a Docker Compose setup to quickly spin up a full Observability Stack for development and testing purposes.

- Loki – High-performance, cost-efficient centralized logging

- Tempo – Distributed tracing backend compatible with OpenTelemetry

- Mimir (or Prometheus) – Scalable metrics storage and querying

- Grafana – Unified UI for logs, traces, metrics, and dashboards

## What This Stack Provides

- Centralized Log Collection from any application using Loki or Promtail

- Distributed Tracing with Tempo (OTLP-compatible)

- Metrics Monitoring via Mimir/Prometheus

- End-to-End Observability in Grafana, including:
    - Logs → Traces correlation
    - Traces → Service performance
    - Metrics → Dashboards & alerts

## Ideal For

- Local development & testing

- Observability PoC or internal demo

- Microservices architecture

- Teams building OpenTelemetry-based infrastructure

- Developers wanting a quick way to explore the full LGTM ecosystem
