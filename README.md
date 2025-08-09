# Log.Cash

Internal repo for Logcomex's cross‑border B2B payments product.

## What’s here
- `crew.yaml` — CrewAI multi‑agent config to generate department deliverables
- `docs/` — Product blueprint + execution plans
- `schemas/` — OpenAPI placeholders
- `diagrams/` — Mermaid diagram sources
- `artifacts/` — Auto‑generated outputs from CrewAI (kept empty in repo)
- `.github/workflows/ci.yml` — Lint + validate on every PR

## Quick start
```bash
python -m venv .venv && source .venv/bin/activate
pip install crewai crewai-tools
export OPENAI_API_KEY=sk-***
export GOOGLE_CSE_ID=***
export GOOGLE_CSE_KEY=***
crewai run -c crew.yaml
```

Use **CrewAI Enterprise** to deploy from this repo or the ZIP.
