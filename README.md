# EduCommMono360Ops

**EduCommMono360Ops** is an educational eCommerce platform built from scratch using a modern monorepo architecture. It incorporates DevOps practices, CI/CD pipelines, Kubernetes orchestration, SRE principles, and full SDLC workflows — designed for personal and educational learning.

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
