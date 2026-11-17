## Ayman Osman: Backend · Software · Forward Deployed Engineer

**Java / Spring Boot · Python / FastAPI · Node.js / TypeScript · Cloud (AWS · Azure · GCP)**

I build backend services and integrations for Saudi government and enterprise clients, usually on site with the people who will use them. For the Emirate of Asir I built and ran the backend behind citizen and employee portals used by **100,000+ people** (about **500K API requests a month**), with Nafath, OTP and Active Directory sign-in and role-based access.

How I work: sit with the client, find the real problem behind the request, ship something small that works, then roll it out and hand it over so the team can run it without me.

📍 Riyadh, Saudi Arabia · Transferable Iqama · Available immediately · [LinkedIn](https://www.linkedin.com/in/ayman-osman-27bb4bb1)

[![AWS Certified Developer – Associate](https://img.shields.io/badge/AWS%20Certified%20Developer-Associate-FF9900?logo=amazonwebservices&logoColor=white)](https://www.credly.com/badges/b32a7071-4b3b-4e33-8e4a-0f34485350a1)
[![Microsoft Certified: Azure AI Cloud Developer Associate](https://img.shields.io/badge/Microsoft%20Certified-Azure%20AI%20Cloud%20Developer-0078D4?logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/api/credentials/share/en-us/aymanosman-4738/423E876A9D287EAA?sharingId=559C0133D1D0C59C)
[![Google Cloud Associate Cloud Engineer](https://img.shields.io/badge/Google%20Cloud-Associate%20Cloud%20Engineer-4285F4?logo=googlecloud&logoColor=white)](https://www.credly.com/badges/c070be89-fd7d-488f-8c8e-22b1b2f2787c)
[![HashiCorp Terraform Associate](https://img.shields.io/badge/HashiCorp-Terraform%20Associate-7B42BC?logo=terraform&logoColor=white)](https://www.credly.com/badges/c00b2a2e-7aff-4a6e-867b-06e6b81b12c7)

### Forward-deployed work

| Project | What it is | Stack |
|---|---|---|
| [WhatsApp booking for a clinic group](https://github.com/coldworld22/fde-case-study) | A full engagement, from on-site discovery to handover: Arabic/English booking on WhatsApp, triage that sends emergencies to 997, Odoo sync that survives outages, pilot and rollout plan, runbook | Python, FastAPI, PostgreSQL, WhatsApp Cloud API, Odoo JSON-RPC, Docker |
| [WhatsApp for Odoo](https://github.com/coldworld22/odoo-whatsapp-integration) | Published Odoo app for WhatsApp Business: invoices, campaigns, inbox, delivery tracking | Python, Odoo 15–19, Meta Cloud API, Odoo tests in CI |
| [Odoo Fleet Maintenance](https://github.com/coldworld22/odoo-fleet-maintenance) | Odoo 17 module: maintenance plans by km or date, automatic service and purchase orders, REST API for telematics | Python, Odoo ORM, Fleet, Purchase, QWeb |

### Backend services

| Project | What it is | Stack |
|---|---|---|
| [Citizen Services API](https://github.com/coldworld22/citizen-services-api) | Government e-services backend: OTP sign-in, role-based access, request workflow, audit trail, AWS deployment | Java 21, Spring Boot 3, PostgreSQL, Testcontainers, Terraform (ECS, RDS) |
| [Integration Gateway](https://github.com/coldworld22/integration-gateway) | Receives signed Stripe and WhatsApp webhooks, stores each once and delivers it to Kafka reliably (outbox, retries, replay) | Java 21, Spring Boot 3, MongoDB, Kafka, Testcontainers |
| [LLM Gateway](https://github.com/coldworld22/llm-gateway) | One OpenAI-compatible API in front of OpenAI, Azure OpenAI and Ollama: fallback, PII masking, per-team limits, token budgets, cost tracking | Java 21, Spring Boot 3, PostgreSQL, Redis, Prometheus |
| [Appointments API on Azure](https://github.com/coldworld22/appointments-api) | Booking backend for government service centres: race-safe slots, Entra ID roles, keyless deployment | .NET 10, Azure SQL, Container Apps, Bicep, OpenTelemetry |
| [PetClinic on Google Cloud](https://github.com/coldworld22/spring-petclinic) | Spring PetClinic made production-ready on GCP with no app changes: private database, secrets, keyless CI/CD | Cloud Run, Cloud SQL, Secret Manager, Terraform |
| [Cognexa](https://github.com/coldworld22/Cognexa-security-ai-lab) | AI workspace with RAG, role-based access and audit logs; runs on local models or on Azure | TypeScript, Express, Next.js, pgvector, Azure OpenAI |
| [SkillBridge](https://github.com/coldworld22/Skillbridge) | Multi-tenant learning and commerce platform: classes, subscriptions, payments, messaging | Node.js, Express, Next.js, PostgreSQL, Redis |

### Libraries and open source

- [saudi-validators](https://github.com/coldworld22/saudi-validators): Java library for Saudi National ID / Iqama, IBAN, mobile and card numbers, with Arabic digits, Bean Validation annotations and reversible PII masking for LLM prompts. Zero dependencies, released on JitPack.
- [accordproject/template-engine #169](https://github.com/accordproject/template-engine/pull/169): merged, regression tests for ordered-list rendering
- [accordproject/template-playground #947](https://github.com/accordproject/template-playground/pull/947): in review

### What I work with

| | |
|---|---|
| **Backend** | Java 21, Spring Boot, Python, FastAPI, Node.js, Express, TypeScript, .NET, REST, WebSockets |
| **Data** | PostgreSQL, MySQL, MongoDB, Redis, Kafka, pgvector, query tuning, data modelling |
| **Security & identity** | JWT, RBAC, OAuth / OTP, Nafath, Entra ID, Active Directory, OWASP Top 10, PDPL |
| **Cloud & DevOps** | Docker, Terraform, Bicep, GitHub Actions, Nginx, Linux, AWS, Azure, Google Cloud |
| **Integrations** | Odoo ERP, WhatsApp Cloud API, Stripe, PayPal, webhooks, LLM APIs, multi-tenant SaaS |

Most of my professional work (government portals, ERP systems) is in private client repositories.

📫 ayman4work44@gmail.com
