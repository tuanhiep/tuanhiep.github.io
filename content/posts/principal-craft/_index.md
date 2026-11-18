---
title: "Production Engineering"
aliases:
  - "/production-engineering/"
  - "/architecture-autopsies/"
  - "/principal-craft/"
  - "/principal/"
  - "/principal/posts/"
description: "Runtime internals, enterprise complexity, lock-free PostgreSQL concurrency, distributed failure autopsies, and safe hybrid reactive/imperative boundaries."
---

Field studies from the boundary where distributed theory collides with production physics, database locks, and runtime schedulers. Every series dissects real failure modes and operational trade-offs:

- **Series 1 — Mastering Enterprise Complexity:** Deterministic strategy routing, orthogonal extension layers, static registries, and immutable zero-cost rollback pipelines.
- **Series 2 — From Contention to Throughput:** Decoupled computation, turning PostgreSQL into a lock-free queue, lease systems under partial failure, and sharding thresholds.
- **Series 3 — Autopsy of Distributed Systems:** Dissecting zombie consumers, thread starvation collapse, broker protocol traps, and silent data loss.
- **Series 4 — Autopsy of a Hybrid Architecture (Complete 4/4):** Why mixing MVC and WebFlux causes thread starvation, temporal rifts in signatures, identity context collapse, and backpressure betrayal.
