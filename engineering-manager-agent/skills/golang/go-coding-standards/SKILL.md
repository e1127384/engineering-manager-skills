---
name: go-coding-standards
description: Apply idiomatic, readable, and maintainable Go coding practices.
---

# Go Coding Standards

- Follow the repository's existing conventions and supported Go version.
- Keep functions focused, names precise, and APIs straightforward.
- Handle errors explicitly; add context when it helps callers act on the error.
- Avoid unnecessary abstraction, mutable shared state, and hidden side effects.
- Preserve compatibility unless the change explicitly permits breaking behavior.
- Format Go source with `gofmt` and run the applicable project checks.
- Add tests for observable behavior, including relevant boundary conditions.
