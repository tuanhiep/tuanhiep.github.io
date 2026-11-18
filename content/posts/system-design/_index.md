---
title: "System Design & AI Infra"
aliases:
  - "/system-design/"
description: "Planetary-scale distributed systems, deterministic matching engines, financial ledgers, flash-sale admission control, and resilient AI/LLM backpressure infrastructure."
---

Field architectures for high-load, correctness-critical software systems. Each series treats an infrastructure problem through its **invariants**, **physical bottlenecks**, and **failure modes**:

- **Series 1 — Stock Exchange Core:** Microsecond order books, LMAX Disruptor matching engines, Event Sourcing, and deterministic HA.
- **Series 2 — Global Payment Gateway:** Idempotency keys, distributed Sagas, double-entry financial ledgers, and automated reconciliation.
- **Series 3 — Global Flash Sale Engine:** Defeating thundering herds, admission control, hot-row inventory sharding, and payment idempotency.
- **Series 4 — The Global Nervous System (AI Infra):** Taming slow, flaky, and expensive LLM consumers with Kafka backpressure and isolation boundaries *(in rollout)*.
