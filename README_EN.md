<p align="center"><img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/main/banner.png" alt="Carlos Felipe — technology portfolio" width="100%"></p>

<h1 align="center">Carlos Felipe</h1>
<p align="center"><a href="README.md">Português</a> · <strong>English</strong></p>
<h2 align="center"><strong>Founder &amp; AI Product Builder | Agents, Automation &amp; Evidence-Based Systems</strong></h2>
<p align="center">I turn business problems into digital products with agents, automation, traceable evidence and human review.</p>

## Featured projects

| Project | Problem and contribution | Stage and demonstration |
| --- | --- | --- |
| [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) | My priority project: deterministic DeFi risk calculations, advisor console and a private diagnostic delivery portal with human review. | PRs under review; browser and disposable Supabase validation with fictional data. [Testing instructions](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/README.md). Private cloud pilot and public demo pending. |
| [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) | Priority project for Agência Camaleão: guided requests, triage, text delivery versions, approval or change requests and history by version/hash. | Deliveries A/B in PRs under review; production and real Supabase Auth/PostgREST/Storage and n8n integrations pending. [Local demo instructions](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/README.md#experimentar-com-dados-fictícios). [Open online demonstration](https://demo-portal.camaleaoweb3.com.br/) — fictional data stored locally in the browser only; public video pending. |
| [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) | Priority project for Agência Camaleão: an AI infrastructure portal, from guided diagnosis to implementation and ongoing operations. | In development. [Public repository](https://github.com/ofelipepeixoto/camaleao-infra-portal) — code available for review. [Online demonstration](https://infra.camaleaoweb3.com.br/) — ChatGPT sign-in required. |
| [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) | Guided evidence organization and deterministic readiness assessment. | Experimental application. [Case study and video](https://github.com/ofelipepeixoto/radar-oaas/blob/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/CASE_STUDY.md). [Open demonstration](https://oaas.camaleaoweb3.com.br/). |
| [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) | Import preview, opportunity triage and assumptions for human review. | Local shadow-mode MVP, no bidding. [Case study and video](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/CASE_STUDY.md). [Open demonstration](https://hermes.camaleaoweb3.com.br/). |
| [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia) | PDF ingestion, page-level review and retrieval with source references. | Local laboratory. [Case study and video](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/CASE_STUDY.md). |

<details>
<summary>Real interfaces using fictional data</summary>

### Document Assistant
![Reviewed PDF retrieval](https://raw.githubusercontent.com/ofelipepeixoto/assistente-documental-ia/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/demo.png)

### Radar OaaS
![Synthetic readiness assessment](https://raw.githubusercontent.com/ofelipepeixoto/radar-oaas/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/demo.png)

### Hermes Leilão RJ
![Fictional financial assumptions in shadow mode](https://raw.githubusercontent.com/ofelipepeixoto/hermes-leilao-rj/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/demo.png)

</details>

### Capital Web3 Advisor — current development

NAV, debt, concentration, stress, impermanent loss and concentrated liquidity calculations; approval, versioned publication, downloads and revocation. The [validation recorded in PR #7](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/homologation.md) includes a browser against the local synthetic portal and, in a separate suite, real Supabase Auth/PostgREST/Storage in a disposable environment, always with fictional data. The [passing CI run](https://github.com/ofelipepeixoto/capital-web3-advisor/actions/runs/38108703715) tested the code from `dd0b539`; only README and documentation changed through head `0ae8bcd`.

PRs remain under review; the private cloud pilot, portal connected to real Auth and production integrations are still pending. OpenAI remains at the contract stage with a fictional adapter and paid usage disabled; MCP is a local example; n8n templates are inactive. Sites and Hostinger remain undeployed. Disposable validation does not authorize production or certify security. No custody or transaction execution. [Architecture](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/architecture.md) · [Backlog](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/backlog.md) · [PRs awaiting review](https://github.com/ofelipepeixoto/capital-web3-advisor/pulls).

## Results and lessons

| Reproduced evidence | Observed result | Conclusion boundary |
| --- | --- | --- |
| Capital Web3 — [synthetic browser scenarios and disposable Supabase](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/homologation.md) | Approval and publication bound to the reviewed version; per-client access and fresh access/downloads denied after revocation in the tested scenarios. | Fictional fixtures; separate browser and backend suites. Does not demonstrate a cloud pilot, production readiness or commercial results; revocation does not retrieve previously downloaded files. |
| Portal Camaleão — [B1/B2 versions and decisions](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/docs/ENTREGA-B2.md) and [CI](https://github.com/ofelipepeixoto/camaleao-portal/actions/runs/38114158773) | Immutable versions/decisions in the SQL contract, conflicts without automatic approval and retries with the same ID without duplicate effects; dates preserved across SQL, driver, triage code and job completion. | Disposable PostgreSQL and browser fixtures; simulated Auth/SDK, no real n8n execution or Supabase Auth/PostgREST/Storage qualification. PRs under review; no commercial evidence. |
| Three-page synthetic digital PDF | 7/7 retrieval cases; unrevised text stays out of results. | Does not measure OCR, real documents or legal quality. |
| Radar OaaS unit/AI tests | 132 passing tests in six files. | Does not validate real Auth/RLS, customer adoption or ROI. |
| Selected Hermes domain/import/regression tests | 33 passing tests. | Does not replace full testing or investment approval. |

Reproductions recorded on 2026-10-11 UTC. Commands, source revisions and limits are in the linked case studies and validation records. Test counts are scoped behavior checks, not productivity or adoption metrics.

## Focus areas

- AI agents, automation, tool and API integration, and MCP contracts with server-side controls.
- Document processing, retrieval and source-grounded answers (RAG).
- Versioned review and publication, per-client authorization and traceable decisions.
- Reproducible tests with fictional data, failure handling, conflicts and retries.
- Model experimentation, budget policies and task routing.
- Digital products for business, content and opportunity analysis.
- Guided request and triage journeys, AI infrastructure and white-label products for Agência Camaleão.
- Web3/DeFi diagnostics with deterministic risk calculations.

## Technologies and tools

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/astro/astro-original.svg" alt="Astro" title="Astro" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/supabase/supabase-original.svg" alt="Supabase" title="Supabase" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40">&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40">&nbsp;
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&amp;logo=n8n&amp;logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&amp;logo=openai&amp;logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/APIs-176B45?style=for-the-badge" alt="APIs">
  <img src="https://img.shields.io/badge/MCP-176B45?style=for-the-badge" alt="MCP">
</p>

I use Vite for the [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/package.json) frontend; Vinext with [D1](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/db/index.ts) in the [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/package.json) implementation under review; and Playwright for browser tests in Portal and [Capital Web3](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/tests/browser/package.json). In Capital, OpenAI is a contract with a fictional adapter, MCP is a local experiment and n8n has inactive templates; in Portal, real n8n execution remains pending.

## Projects and initiatives

The Radar ecosystem evolves through reviewable steps. These repositories include products in development, experimental libraries and laboratories; their READMEs describe verified scope and current limits.

### Integrations, evidence and models

- [Radar Integration Hub](https://github.com/ofelipepeixoto/radar-integration-hub) — governed integration laboratory, restricted tools and human review; external services are not yet qualified.
- [Radar Evidence Kit](https://github.com/ofelipepeixoto/radar-evidence-kit) — experimental evidence contracts, receipts and provenance library.
- [Radar Model Router](https://github.com/ofelipepeixoto/radar-model-router) — local task-routing and budget experiments; no model calls.

### Documents and evaluation

- [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia) — local PDF ingestion, page review and source retrieval.
- [Legal retrieval evaluation](https://github.com/ofelipepeixoto/avaliacao-rag-juridico) — document retrieval evaluation with fictional contracts.
- [Retrieval laboratory](https://github.com/ofelipepeixoto/laboratorio-busca-rag) — comparison of retrieval methods on educational datasets.
- [Human approval agent](https://github.com/ofelipepeixoto/agente-aprovacao-humana) — local demonstration of proposals, explicit approval and restricted execution.
- [Source review](https://github.com/ofelipepeixoto/skill-revisao-de-fontes) — original skill for evidence tracing and uncertainty disclosure.

### Ecosystem products and initiatives

- [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) — guided requests and triage for social assets, campaigns, websites and automation, with text versions, approval or change requests and history by version/hash. Deliveries A/B in PRs under review; demo uses fictional local data only, production and real Supabase Auth/PostgREST/Storage and n8n integrations pending. Separate from Camaleão Infra Portal, which focuses on AI infrastructure diagnosis and operations.
- [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) — priority project in development for [Agência Camaleão](https://camaleaoweb3.com.br/); [public repository](https://github.com/ofelipepeixoto/camaleao-infra-portal), public code and [online demonstration](https://infra.camaleaoweb3.com.br/) requiring ChatGPT sign-in.
- [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) — advisor console and private diagnostic delivery with approval, versioned publication and revocation; synthetic browser scenarios and disposable Supabase Auth/PostgREST/Storage validated with fictional data. PRs under review; private cloud pilot, public demo and production integrations pending.
- [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) — experimental readiness assessment for outcome-oriented businesses.
- [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) — shadow-mode opportunity triage and dossiers with human review; no bids.
- [Help Mídias](https://github.com/helpmidias-ia) · [Radar Tech News](https://github.com/radartech-news) · [Radar Disruptivo](https://radardisruptivo.com.br/) · [Agência Camaleão](https://camaleaoweb3.com.br/).

## Writing and collaboration

I connect editorial analysis and product development at [Radar Disruptivo](https://radardisruptivo.com.br/):

- [Persistent agents and governance](https://radardisruptivo.com.br/noticias/openai-dots-agentes-persistentes-governanca) — identity, permissions, cost and human responsibility (Portuguese).
- [MCP, security and governance](https://radardisruptivo.com.br/noticias/mcpa-certificacao-oficial-model-context-protocol) — editorial context for tool contracts and boundaries (Portuguese).

These articles discuss industry context; they do not certify or validate the project implementations.

The `CONTRIBUTING.md` guides suggest small, verifiable tasks:

- [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/CONTRIBUTING.md): add a fictional two-column PDF, record extraction failures and run `python avaliar_pdf.py --strict`, preserving approval requirements.
- [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/27be19ee47e018337d4ca9778ffed71845561de1/CONTRIBUTING.md): add fictional CSVs with missing prices or ambiguous property types, document how the import preview flags them and run `npm run test:unit`.
- [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/a52d2a9b671f0cc952c5fa75eed3689071041679/CONTRIBUTING.md): improve a PT/EN term and a fictional example distinguishing unknown data from unfavorable evidence; run `npm run test:unit`.

Use reproducible fixtures, explicit expected results and a record of limits and checks. For Capital Web3 Advisor, follow its README, backlog and PRs under review. AI tools assist development; product decisions, review and boundaries remain explicit.

## Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Felipe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ofelipepeixoto/)
[![GitHub](https://img.shields.io/badge/GitHub-ofelipepeixoto-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ofelipepeixoto)
[![Radar Disruptivo](https://img.shields.io/badge/Site-Radar%20Disruptivo-176B45?style=for-the-badge)](https://radardisruptivo.com.br/)
[![Agência Camaleão](https://img.shields.io/badge/Site-Agência%20Camaleão-071007?style=for-the-badge&labelColor=176B45)](https://camaleaoweb3.com.br/)

## 📈 GitHub statistics

<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/stats.svg" alt="Estatísticas públicas do GitHub de Carlos Felipe" width="49%">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/top-langs.svg" alt="Linguagens dos repositórios públicos de Carlos Felipe" width="49%">
</p>

Updated daily through GitHub Actions. Language distribution represents public code, not proficiency or hours worked; the profile and selected imported/reference projects are excluded from the language card.

## Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake.svg" alt="Animação de uma cobrinha percorrendo minhas contribuições no GitHub" width="100%">
  </picture>
</p>
