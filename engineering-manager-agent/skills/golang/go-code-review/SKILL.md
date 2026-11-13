---
name: go-code-review
description: Review Go changes for correctness, safety, and maintainability.
---

# Go Code Review

Review the change against its intended behavior and surrounding code. Prioritize
issues that could cause incorrect results, crashes, data loss, security
exposure, races, compatibility breaks, or missing regression coverage.

For each finding, include a severity, precise location, concrete impact, and
actionable fix. Check error paths, resource cleanup, context cancellation,
concurrent access, and boundary inputs where applicable. Do not report style
preferences as defects.
