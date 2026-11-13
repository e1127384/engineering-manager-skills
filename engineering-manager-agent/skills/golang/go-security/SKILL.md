---
name: go-security
description: Assess common security risks in Go code and dependencies.
---

# Go Security

1. Identify trust boundaries, sensitive data, and security assumptions.
2. Validate and constrain untrusted input at the point it enters the system.
3. Use parameterized operations and safe standard-library APIs; avoid unsafe
   interpretation of paths, commands, templates, and serialized data.
4. Apply least privilege, safe error responses, and secure secret handling.
5. Check dependency and authentication changes against project policy.
6. Add regression coverage and report residual risks and deployment controls.
