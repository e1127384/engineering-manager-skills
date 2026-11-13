# Organization Context

Use this as the shared knowledge base for all project and release roles. Treat
only confirmed values as facts; fill the project registry from approved
organization sources before using project-specific names, owners, or paths.

## Organization structure

```text
CEO
├── Senior Project Manager
│   └── Project Manager — one assigned to each of the 8 projects
└── Senior Release Manager
    └── Release Manager — one assigned to each of the 8 projects
```

Senior managers coordinate and report across the portfolio. Project managers
and release managers own coordination for their assigned project. This chart
describes delivery reporting and does not imply personnel-management authority.

## Portfolio and project setup

- The organization has 8 projects. Each has a dedicated squad and Azure DevOps
  area path; do not reuse another project's path.
- Each project has 5–8 Azure DevOps repositories. Common repository purposes
  include UI, backend-for-frontend, process API, LPP, and documentation; verify
  each project's actual repository list rather than assuming this is exhaustive.
- Backend implementations may use Java, Python, or Go. Confirm a repository's
  language and stack from its source before applying language-specific guidance.
- Pipelines build and deploy repositories through SIT, UAT, QA, and PROD.
- Every project manager and release manager is assigned to one project; the
  corresponding senior role handles cross-project coordination and reports to
  the CEO.

## Project registry

Replace placeholders using verified Azure DevOps and organization records.

| Project | Squad | Area path | Project manager | Release manager | ADO repositories and purpose | Backend stack |
|---|---|---|---|---|---|---|
| Project 1 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 2 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 3 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 4 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 5 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 6 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 7 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |
| Project 8 | TBD | TBD | TBD | TBD | TBD (5–8 repos) | TBD |

## Work tracking

- Use the hierarchy **Epic → Feature → Story → Sub-task** and preserve links
  between parent and child items.
- Plan quarterly backlogs and delivery sprints using each project's squad,
  area path, capacity, and ADO conventions.
- Confirm the target project and area path before creating or changing work
  items. Keep cross-project dependencies explicitly linked and owned.

## Release and shared controls

- Each release is represented by a release work item. It identifies every
  repository being released and links the release's related work items.
- Every repository's ADO pipeline should retain traceability to that release
  work item and its source revision through SIT, UAT, QA, and PROD.
- Apply organization-level solution-intent and security-control requirements
  consistently across projects. Link the relevant control work items or
  evidence to the release; do not duplicate or silently waive shared controls.
- Treat environment progression, readiness gates, approvals, and production
  changes according to the organization's current policies. Verify policy
  details instead of inferring them from this context.
