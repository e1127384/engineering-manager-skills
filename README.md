
Implement this as a skills repository for a senior engineering manager who manages projects developed in golang and then devops and project tracking via azure workitems, repositories, release plan and pipelines.

engineering-manageragent/
│
├── AGENTS.md
├── README.md
│
├── agents/
│   ├── orchestrator.md
│   ├── golang-engineer.md
│   ├── code-reviewer.md
│   ├── project-manager.md
│   └── release-manager.md
│
├── skills/
│   ├── golang/
│   │   ├── go-architecture/SKILL.md
│   │   ├── go-coding-standards/SKILL.md
│   │   ├── go-testing/SKILL.md
│   │   ├── go-concurrency/SKILL.md
│   │   ├── go-security/SKILL.md
│   │   ├── go-observability/SKILL.md
│   │   └── go-code-review/SKILL.md
│   │
│   ├── project-management/
│   │   ├── backlog-management/SKILL.md
│   │   ├── sprint-planning/SKILL.md
│   │   ├── work-item-management/SKILL.md
│   │   ├── dependency-tracking/SKILL.md
│   │   └── project-status-report/SKILL.md
│   │
│   ├── release-management/
│   │   ├── release-planning/SKILL.md
│   │   ├── release-readiness/SKILL.md
│   │   ├── changelog-generation/SKILL.md
│   │   ├── pipeline-monitoring/SKILL.md
│   │   ├── deployment-validation/SKILL.md
│   │   └── rollback-planning/SKILL.md
│   │
│   └── devops/
│       ├── ado-work-items/SKILL.md
│       ├── ado-repositories/SKILL.md
│       ├── ado-pipelines/SKILL.md
│       └── ado-pull-requests/SKILL.md
│
├── config/
│   ├── mcp.json
│   └── environments.yaml
│
└── workflows/
    ├── feature-development.md
    ├── bug-fix.md
    ├── sprint-review.md
    └── production-release.md
