<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/main/banner.png" alt="Carlos Felipe — AI engineering portfolio" width="100%">
</p>

<h1 align="center">Carlos Felipe</h1>
<p align="center"><a href="README.md">Português</a> · <strong>English</strong></p>

I build digital products and AI experiments that help teams and clients organize evidence, make decisions and navigate clearer workflows. My work spans problem definition, implementation and human review, with explicit boundaries around what has actually been tested. This portfolio brings together automation, content, infrastructure and Web3 initiatives at different stages.

## Featured projects

| Project | Problem, solution and contribution | Stage and where to look |
| --- | --- | --- |
| [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) | DeFi advisory work needs risk calculations and reviewed reports without executing transactions. I develop the deterministic engine, review console and versioned delivery portal. | The [staging domain](https://capital.camaleaoweb3.com.br/) is active and points to Site v2; the [synthetic cloud flow](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/631dc69591a01b5218493e501fe581900a7ea416/docs/evidence/cloud-staging-2026-10-17.md) is documented in [PR #12](https://github.com/ofelipepeixoto/capital-web3-advisor/pull/12), stacked and outside `main`. Do not enter real data: customer access, a pilot and production have not been validated. |
| [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) | AI infrastructure needs a guided diagnosis, reviewed plan and ongoing support. I shape this Agência Camaleão product and its review journey. | [`main` contains a plan and an offline reference](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/71f9102792ac2a4e7b6156a85f24d9e4636bb4f7/README.md); persistent intake and review are in [stacked PRs](https://github.com/ofelipepeixoto/camaleao-infra-portal/pulls). Branch CI does not establish deployment or customer validation. |
| [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) | Requests for creative assets, campaigns, websites and automation can lose context. I built guided briefs, triage, text delivery versions and approval or change requests. This is separate from the infrastructure portal. | Deliveries A/B and guided review [merged into `main`](https://github.com/ofelipepeixoto/camaleao-portal/commits/main/). [Local demo instructions with fictional data](https://github.com/ofelipepeixoto/camaleao-portal/blob/6acae7ad977cef31eef0d284a7bcffa40e9f20ba/README.md#experimentar-com-dados-fict%C3%ADcios); real Supabase Auth/PostgREST/Storage, n8n and operational use still need validation. |
| [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) | Founders need to see which evidence is missing before advancing an opportunity. I built a guided assessment that separates missing data, rules and human review. | Experimental app on `main`. [Case study, screenshot and video with a synthetic example](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/docs/portfolio/CASE_STUDY.md); no evidence of adoption or financial outcomes. |
| [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) | Property auction analysis requires source checks, import review and explicit assumptions before decisions. I built an import preview, triage and dossier with visible unknowns. | Local shadow-mode MVP, no bids. [Case study, screenshot and fictional video](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/docs/portfolio/CASE_STUDY.md); not investment advice. |
| [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia) | PDF retrieval needs source references and page-level checking. I built ingestion, correction and approval of passages before source-grounded search. | Local laboratory. [Case study, screenshot and video with a fictional PDF](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/docs/portfolio/CASE_STUDY.md); real documents and OCR have not been validated. |

<details>
<summary>View interfaces run with fictional data</summary>

### Document Assistant
![Reviewed PDF retrieval](https://raw.githubusercontent.com/ofelipepeixoto/assistente-documental-ia/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/demo.png)

### Radar OaaS
![Synthetic readiness assessment](https://raw.githubusercontent.com/ofelipepeixoto/radar-oaas/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/demo.png)

### Hermes Leilão RJ
![Fictional financial assumptions in shadow mode](https://raw.githubusercontent.com/ofelipepeixoto/hermes-leilao-rj/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/demo.png)

</details>

## Results and lessons

- **Versioned review:** in [Capital Web3](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/631dc69591a01b5218493e501fe581900a7ea416/docs/evidence/cloud-staging-2026-10-17.md), the recorded synthetic cloud validation exercised hosted Auth/RLS and Edge with fictional accounts: independent review, publication to an exact recipient, download, receipt and revocation. [PR #12 CI](https://github.com/ofelipepeixoto/capital-web3-advisor/actions/runs/39064591404) passed on the branch SHA; that does not validate customers, MFA, attachments, host headers or production. Revocation cannot retrieve an already downloaded file.
- **Conflicts and retries:** [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal/blob/6acae7ad977cef31eef0d284a7bcffa40e9f20ba/docs/ENTREGA-B2.md) preserves versioned decisions and tests repeat requests without duplicate effects. Browser fixtures and a disposable database do not replace real integration validation.
- **Visible uncertainty:** [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/docs/portfolio/CASE_STUDY.md) keeps insufficient evidence pending; [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/docs/portfolio/CASE_STUDY.md) retains unknown financial fields; [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/docs/portfolio/CASE_STUDY.md) excludes unapproved text from retrieval. These case studies use fictional data and do not measure adoption, customer effectiveness or revenue.

## Focus areas

- Products with agents and automation, bounded tools, human approval and explicit failures.
- Document processing and retrieval with sources, versions and evaluation.
- Model experiments, task routing and budget controls.
- Digital request journeys, diagnosis and editorial content.
- Web3/DeFi risk analysis and opportunity triage without financial execution.

## Technologies and tools

I use **Python** for deterministic engines and document laboratories; **TypeScript, Vite and Playwright** in Portal Camaleão; **Astro and React** in Radar OaaS; and **PostgreSQL and Supabase** in authorization and persistence tests and synthetic validation. The Infra Portal implementation under review uses **Vinext and D1** ([code](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/db/index.ts)). **n8n** appears in contracts and inactive templates in the cited projects; **MCP** in local examples; **OpenAI** in Capital remains a fictional adapter with paid usage disabled. These are concrete uses, not claims of production integrations.

## Projects and initiatives

**Integrations and evidence.** [Radar Integration Hub](https://github.com/ofelipepeixoto/radar-integration-hub) studies governed tools with local demonstrations; [Radar Evidence Kit](https://github.com/ofelipepeixoto/radar-evidence-kit) develops experimental evidence contracts, receipts and provenance. External integrations remain within each repository's documented scope.

**Models and learning.** [Radar Model Router](https://github.com/ofelipepeixoto/radar-model-router) makes local model-tier and budget recommendations without calling models; its notices attribute a third-party policy used as a reference. The [FT05 PRs](https://github.com/ofelipepeixoto/radar-model-router/pulls) prepare a synthetic corpus and evaluation, without verified full training or benchmarking. [Radar Classificador Colab](https://github.com/ofelipepeixoto/radar-classificador-colab) is an educational extraction in [draft PRs](https://github.com/ofelipepeixoto/radar-classificador-colab/pulls); it is not yet a validated tutorial or a model for real customer service.

**Documents and review.** [Legal retrieval evaluation](https://github.com/ofelipepeixoto/avaliacao-rag-juridico) uses fictional contracts; [RAG search laboratory](https://github.com/ofelipepeixoto/laboratorio-busca-rag) compares retrieval methods; [Human approval agent](https://github.com/ofelipepeixoto/agente-aprovacao-humana) demonstrates restricted execution after confirmation; [Source review](https://github.com/ofelipepeixoto/skill-revisao-de-fontes) organizes evidence and uncertainties.

**Ecosystem and content.** [Radar Tech News](https://github.com/radartech-news), [Help Mídias](https://github.com/helpmidias-ia), [Radar Disruptivo](https://radardisruptivo.com.br/) and [Agência Camaleão](https://camaleaoweb3.com.br/) are ecosystem initiatives; the Camaleão portals above serve distinct journeys within the same agency.

## Writing and collaboration

At [Radar Disruptivo](https://radardisruptivo.com.br/), I connect editorial analysis and product decisions. Read the Portuguese articles on [persistent agents and governance](https://radardisruptivo.com.br/noticias/openai-dots-agentes-persistentes-governanca) and [MCP, security and governance](https://radardisruptivo.com.br/noticias/mcpa-certificacao-oficial-model-context-protocol). The articles provide context; they do not certify the projects.

Start with the featured case studies and videos to explore the work. For contributions using fictional examples and reproducible checks, see the guides for [Document Assistant](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/CONTRIBUTING.md), [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/CONTRIBUTING.md) and [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/CONTRIBUTING.md).

## Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Felipe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ofelipepeixoto/)
[![GitHub](https://img.shields.io/badge/GitHub-ofelipepeixoto-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ofelipepeixoto)
[![Radar Disruptivo](https://img.shields.io/badge/Site-Radar%20Disruptivo-176B45?style=for-the-badge)](https://radardisruptivo.com.br/)
[![Agência Camaleão](https://img.shields.io/badge/Site-Agência%20Camaleão-071007?style=for-the-badge&labelColor=176B45)](https://camaleaoweb3.com.br/)

## 📈 GitHub statistics

<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/stats.svg" alt="Public GitHub statistics for Carlos Felipe" width="49%">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/top-langs.svg" alt="Languages in Carlos Felipe's public repositories" width="49%">
</p>

Updated daily through GitHub Actions. Language distribution reflects public code, not proficiency or hours worked; the profile and selected imported/reference repositories are excluded from the language card.

## Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake.svg" alt="Animated snake crossing my GitHub contribution grid" width="100%">
  </picture>
</p>
