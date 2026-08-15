# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. The goal is to give new team members a quick orientation and a single place to find the project artifacts, templates, checklists, and escalation paths used across our projects.

OctoAcme follows an iterative, customer-first approach to delivery. Work starts with project initiation (one-pager + stakeholder alignment), proceeds into planning (backlog, estimates, Definition of Done), and moves into execution with named owners for delivery (Project Manager) and outcomes (Product Lead). We favour small, testable increments and use prioritized backlogs and regular planning to keep scope manageable.

Our team rhythm includes daily standups for progress and blockers, a weekly delivery sync for cross-team coordination and risk review, and demos/reviews at the end of each sprint or milestone. Pull requests should be small when possible, include acceptance criteria and an issue link, run CI and security checks, and require at least one approval before merging.

Quality gates include unit and integration tests, security scanning in CI, and smoke tests for critical flows before release. Releases follow a checklist-driven process with pre-release verifications, automated pipelines where possible, rollback/mitigation plans, and post-deploy verifications. We maintain a simple risk register that is reviewed regularly and use dashboards to monitor key signals (errors, latency, usage).

How to use these docs
- Read the overview above for a quick orientation.
- Open any linked document below for detailed policies, templates, and checklists.
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose updates to these process documents.

Links to process documents
- [Project management overview](octoacme-project-management-overview.md)
- [Project initiation guide](octoacme-project-initiation.md)
- [Project planning](octoacme-project-planning.md)
- [Execution & tracking](octoacme-execution-and-tracking.md)
- [Risks & communication](octoacme-risks-and-communication.md)
- [Release & deployment](octoacme-release-and-deployment.md)
- [Retrospective & continuous improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & personas](octoacme-roles-and-personas.md)
