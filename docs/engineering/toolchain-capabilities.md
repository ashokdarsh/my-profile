---
title: Ashok's Profile - Engineering Toolchain & CI/CD - Capabilities
permalink: false
hide:
---

# Toolchain Capabilities Across the SDLC

## Planning & Agile Management
- Jira and Azure Boards for backlog management, sprint planning, and team collaboration
- GitHub issues integrated with stories and commits
- Real-time dashboards and velocity tracking

## Source Control & Branch Strategy
- GitHub Enterprise as the enterprise SCM
- GitFlow and GitHubFlow with feature/release/hotfix branches
- Required PR reviews, branch protections, semantic commits
- Tagging strategy tied to CI/CD pipeline deployments

## CI/CD Automation
- go-Vela, GitHub Actions, and Azure Pipelines
- Triggered builds on PR creation, merges, and tags
- CI steps include linting, unit tests, coverage, static scans, and Docker builds
- CD steps push to Dev, Stage, and Prod environments with traceability

## Security & Quality Gates
- **Code Quality**: SonarQube static analysis and linting
- **Security**: Checkmarx scans integrated into CI
- **Coverage**: NUnit / JUnit in the pipeline
- **Secrets Management**: CI-integrated secrets, vaults, and secure param stores
- **Dependency Scanning**: SBOM generation, vulnerability alerts

## Testing Strategy
- Automated testing baked into pipelines: unit, functional, regression, and security tests
- Shift-left approach: testing and scanning happen at the PR level
- Contract testing (e.g., Pact) and test data management where needed

## Containerization & IaC
- Docker and Kubernetes for service packaging and orchestration
- Terraform modules for infrastructure provisioning
- Helm charts for deployment consistency
- Environments managed through the CI/CD pipeline

## Observability & Monitoring
- Datadog for log aggregation, APM, real-time metrics
- Custom dashboards, alert thresholds, and health checks
- Opsgenie for alert routing and on-call scheduling

## Collaboration & Notifications
- GitHub PR comments, automated CI status updates
- MS Teams ChatOps integration for build alerts and incident comms
- Traceability from story → code → test → deploy