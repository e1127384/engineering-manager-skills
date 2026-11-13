---
name: portfolio-release-coordination
description: Coordinate repository-based releases across projects and environments.
---

# Portfolio Release Coordination

1. Confirm the release owner, target date, included projects, and release work
   item from Azure DevOps.
2. Verify that the release work item enumerates each included repository and
   links the related delivery, solution-intent, and security-control work items.
3. For each repository, record its source revision, pipeline run, accountable
   release manager, and readiness evidence.
4. Coordinate dependency order and readiness across SIT, UAT, QA, and PROD.
   Apply each environment's current approval and promotion policy.
5. Block or escalate releases with missing required controls, failed readiness
   gates, unclear ownership, or unverified artifact provenance.
6. Consolidate outcomes and unresolved risks for the Senior Release Manager;
   never treat one repository's success as proof that the full release is ready.
