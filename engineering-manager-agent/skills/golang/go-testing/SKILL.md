---
name: go-testing
description: Build focused, reliable tests for Go behavior and regressions.
---

# Go Testing

1. Identify public behavior and the regression or requirement to protect.
2. Prefer small table-driven tests for related input/output cases.
3. Cover success, error, boundary, and relevant cancellation or timeout paths.
4. Keep tests deterministic; avoid timing assumptions and shared mutable state.
5. Use integration tests only where package-level tests cannot verify the
   important contract.
6. Run targeted tests first, then broader project checks when practical.
