# Julian Piedrahita

**AI & Data Lead · End-to-end builder · Madrid, Spain**

I lead the AI and Data function for a multinational food distribution company operating between Spain and Mexico. I design, build and ship AI agents, data platforms and SAP-integrated systems end to end — from architectural decisions and partner alignment to production code.

---

## What I work on

I sit at the intersection of three areas most teams keep separate:

- **Modern data platforms** — lakes on Delta, Spark, dbt, Airflow, feature stores, governance and MLOps.
- **LLM applications in production** — LangGraph agents, RAG with vector databases, Anthropic Claude and Azure OpenAI, with formal evaluation in CI.
- **Deep enterprise integrations** — SAP (Service Layer + SQL), Microsoft Graph, Teams, Power BI, EDI.

Most of what I build combines a real operational problem, an enterprise system as the source of truth (typically SAP), and a modern data or AI layer that turns information into action. I care about systems that actually run on Monday morning, not demos.

---

## Current focus

I am building a portfolio of three reference platforms that consolidate everything I have learned about modern data and AI engineering. Each one targets a different domain and demonstrates a different part of the stack:

- **PurchaseIQ** — Intelligent procurement platform for food distribution. Demand forecasting, inventory optimisation, multi-criteria supplier selection, and an autonomous purchasing agent integrated with SAP and Microsoft Teams. *In development.*
- **HIV DataOps** — Reference data governance platform for global HIV surveillance, with strong emphasis on privacy engineering, Collibra-equivalent cataloguing, and AI-assisted governance. *In development.*
- **FamineWatch** — Multi-modal humanitarian data platform integrating satellite imagery, conflict event streams, market prices and household surveys to forecast food insecurity in fragile states. *In development.*

Each platform ships with full Terraform IaC, governance layers, MLOps, agent evaluation, and an honest README documenting what is built, what is in progress, and what is roadmap.

---

## Selected work

### Internal products (code private)

- **B2B logistics platform** — Full-stack SaaS for customer-facing logistics with real-time SAP Business One integration. FastAPI + React 19 + PostgreSQL + Docker. 13 domain models, three-tier role-based access, Microsoft Graph integration, 8-state order lifecycle.
- **WhatsApp ordering agent** — Conversational ordering agent powered by Anthropic Claude with SAP Service Layer backend. Customers place and track orders through natural language.
- **Procurement intelligence platform** — Demand forecasting, supplier scoring and an autonomous purchasing agent with human-in-the-loop approval, integrated with SAP.

### Public repositories

- [`agent-picklight-showcase`](https://github.com/ImJulian1992/agent-picklight-showcase) — Case study of a production warehouse operations platform: Claude-powered Teams agent with SAP Business One integration, FEFO allocation, and Circuit route dispatch.
- `hr-attendance-graph-showcase` — HR attendance automation case study built on Microsoft Graph API. *Coming soon.*

---

## Tech stack

| Domain | Tools I use regularly |
|---|---|
| Languages | Python, SQL, TypeScript, Bash |
| Data engineering | Delta Lake, dbt, Spark, Airflow, DuckDB, Polars, Pydantic |
| ML / forecasting | LightGBM, scikit-learn, statsforecast, PyTorch Forecasting |
| Optimisation | OR-Tools, PuLP |
| GenAI / agents | LangGraph, Anthropic Claude API, Azure OpenAI, Qdrant, Ragas |
| MLOps | MLflow, Feast, Evidently, Fairlearn |
| Backend | FastAPI, SQLAlchemy, Alembic |
| Frontend | React, Next.js, Tailwind, shadcn/ui, Streamlit |
| ERP / enterprise | SAP Business One (Service Layer + SQL), Microsoft Graph API, Teams |
| Cloud | Azure (ADLS, Databricks, ML, OpenAI, Container Apps), Digital Ocean |
| IaC / DevOps | Terraform, Docker, GitHub Actions (OIDC), pre-commit |
| Governance | Collibra (equivalence), Microsoft Purview, DataHub, OpenLineage, Great Expectations |

---

## Get in touch

- LinkedIn: [julian-piedrahita](https://www.linkedin.com/in/julian-piedrahita/)
- Personal site: *coming soon*
- Email: *coming soon*

---

<sub>Profile last updated: April 2026. Pinned repositories will be updated as the portfolio platforms ship publicly.</sub>
