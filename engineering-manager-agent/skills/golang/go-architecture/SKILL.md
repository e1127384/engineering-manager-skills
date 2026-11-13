---
name: go-architecture
description: Design and evaluate maintainable Go package and service structures.
---

# Go Architecture

## Procedure

1. Clarify requirements, runtime constraints, and compatibility expectations.
2. Inspect existing packages, public APIs, dependency direction, and deployment
   boundaries before proposing a structure.
3. Keep packages cohesive and APIs small; depend on abstractions only where they
   improve a real boundary or test seam.
4. Make ownership, data flow, and failure behavior explicit.
5. Compare alternatives against complexity, operability, and likely change.
6. Document material trade-offs and validate the design with focused tests or a
   small implementation when appropriate.
