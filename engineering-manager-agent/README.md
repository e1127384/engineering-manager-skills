# Engineering Manager Agent

A toolkit for coordinating engineering delivery across Go development, project
management, release management, and Azure DevOps.

## Contents

- `agents/` — role instructions and responsibilities.
- `skills/` — reusable procedures for focused tasks.
- `context/` — organization-wide operating context and project registry.
- `config/` — MCP and environment examples.
- `workflows/` — coordinated, end-to-end delivery playbooks.

## Getting started

1. Read [AGENTS.md](AGENTS.md) for shared operating principles.
2. Read `context/organization.md` for the portfolio structure and project
   context. Replace its project placeholders with verified organization data.
3. Select the role in `agents/` that best fits the request; use
   `orchestrator.md` when work spans multiple roles. Project managers and
   release managers coordinate their assigned project; their senior roles
   coordinate across the portfolio and report to the CEO.
4. Load the relevant role skills and the organization-level skills for
   solution intent and security controls.
5. Configure integrations using `config/mcp.json` and
   `config/environments.yaml`. Replace example values with locally managed
   settings, and keep credentials in environment variables or a secret store.

All plans should identify the goal, scope, owner, dependencies, risks, and
completion criteria. Verify results before reporting completion.
