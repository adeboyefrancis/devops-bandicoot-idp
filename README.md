# DevOps Bandicoot Northstar Platform

> Internal Request / Asset / Workflow Platform — built as a learning compass for DevOps, Cloud, and Platform Engineering.

## What is Devops Bandicoot Northstar?

This is a realistic internal platform application used as the anchor project across a full DevOps/Platform Engineering learning path. Every phase of the learning roadmap adds a new layer to this app.

| Phase | What gets added                     |
| ----- | ----------------------------------- |
| P1–P2 | CI pipeline, Docker, FastAPI, tests |
| P3    | Terraform cloud environment         |
| P4    | Helm chart, ArgoCD GitOps           |
| P5    | Kyverno policies, observability     |
| P6    | SLOs, reusable platform patterns    |

## Local setup

```bash
make run      # Start the app
make test     # Run tests
make lint     # Lint the code
make help     # See all commands
```

## Stack

- **Backend**: Python + FastAPI
- **Database**: PostgreSQL
- **Containers**: Docker + Compose
- **CI/CD**: GitHub Actions
- **IaC**: Terraform (Phase 3+)
- **K8s**: Helm + ArgoCD (Phase 4+)
