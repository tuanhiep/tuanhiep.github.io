---
title: "Designing a Product-Matching Orchestrator at Scale"
date: 2025-08-29
tags: ["system-design", "distributed-systems", "kafka", "orchestration"]
summary: "Retries, idempotency, backpressure, and lessons from real-time matching."
draft: false
---

## Problem
Mô tả yêu cầu, SLA, traffic, dữ liệu.

## Architecture (High Level)
Kafka topics, consumer groups, orchestrator, DLQ, retry policy (exponential/backoff), idempotency keys.

## Key Trade-offs
- Orchestration vs Choreography
- Exactly-once-ish & Idempotency
- Backpressure & Rate limiting

## Failures & Lessons
Hot partitions, poison messages, observability (metrics/logs/tracing).

## What I'd do differently
Dynamic throttling, adaptive batching, autoscaling signals.