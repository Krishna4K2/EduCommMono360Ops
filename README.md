# EduCommMono360Ops

**EduCommMono360Ops** is an educational eCommerce platform built from scratch using a modern monorepo architecture. It incorporates DevOps practices, CI/CD pipelines, Kubernetes orchestration, SRE principles, and full SDLC workflows — designed for educational learning.

---

## 📁 Repository Structure

```text
EduCommMono360Ops/
├── apps/                  # Frontend and backend applications
│   ├── frontend/          # (e.g., React, Next.js)
│   └── backend/           # (e.g., Go, Python APIs)
├── services/              # Microservices like auth, cart, payments, etc.
├── libs/                  # Shared code libraries (utils, types)
├── infra/                 # Infrastructure code
│   ├── k8s/               # Kubernetes manifests
│   └── terraform/         # Terraform scripts (cloud provisioning)
├── docs/                  # Internal documentation portal (Backstage/Docusaurus)
├── .github/workflows/     # CI/CD pipelines using GitHub Actions
├── .env.example           # Environment variable template
└── README.md              # This file
```

---

✅ This structure helps organize the entire project in a scalable and modular way, simulating real-world enterprise architecture.

---

## 🌿 Branch Naming Convention

This project follows a structured branch naming strategy for clarity, consistency, and scalability:

| Prefix         | Purpose                                | Example                                      |
|----------------|----------------------------------------|----------------------------------------------|
| `feat/`        | New features                           | `feat/add-user-auth`                         |
| `fix/`         | Bug fixes                              | `fix/cart-price-bug`                         |
| `docs/`        | Documentation updates                  | `docs/add-readme-structure`                  |
| `chore/`       | Maintenance tasks                      | `chore/update-eslint-config`                 |
| `refactor/`    | Code restructuring (no behavior change)| `refactor/split-order-service`               |
| `test/`        | Adding or updating tests               | `test/integration-order-api`                 |
| `infra/`       | Infrastructure changes (K8s, Terraform)| `infra/k8s-deployments`                      |
| `ci/` / `cd/`  | CI/CD pipeline changes                 | `ci/add-gh-actions-backend-pipeline`         |
| `release/`     | Preparing a release                    | `release/v1.0.0`                             |

> ✅ Use lowercase letters and dashes. Keep branch names short and descriptive.

---

