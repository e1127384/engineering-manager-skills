---
name: go-concurrency
description: Design and review safe Go concurrency and cancellation behavior.
---

# Go Concurrency

- Define goroutine ownership, lifetime, and shutdown behavior.
- Propagate cancellation with `context.Context`; do not store contexts in
  long-lived structs.
- Synchronize shared mutable state or redesign to avoid sharing it.
- Ensure channels have clear send/receive ownership and termination behavior.
- Bound worker counts, queues, and external work where resource use matters.
- Test races and cancellation paths using the project's available Go checks.
