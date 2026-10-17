<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/main/banner.png"
       alt="Banner de Carlos Felipe — engenharia de IA"
       width="100%">
</p>

<h1 align="center">Carlos Felipe</h1>
<p align="center"><strong>Português</strong> · <a href="README_EN.md">English</a></p>
<h2 align="center"><strong>Founder & AI Product Builder | Agentes, automação e produtos com evidências rastreáveis e revisão humana | Ecossistema Radar</strong></h2>
<p align="center">
  Transformo problemas de negócio em produtos digitais com agentes, automações, evidências rastreáveis e revisão humana.
</p>

## Projetos em destaque

| Projeto | Problema e contribuição | Estágio e demonstração |
| --- | --- | --- |
| [Capital Web3 Advisor](https://capital.camaleaoweb3.com.br/) | Uma consultoria DeFi precisa calcular riscos e entregar diagnósticos revisados sem executar transações. Desenvolvo o motor determinístico, o console de revisão e um portal de entrega por versão. | O domínio aponta para o Site v2 de homologação. [Código e documentação](https://github.com/ofelipepeixoto/capital-web3-advisor) · [evidência do fluxo sintético em nuvem](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/631dc69591a01b5218493e501fe581900a7ea416/docs/evidence/cloud-staging-2026-10-17.md) · [PR #12](https://github.com/ofelipepeixoto/capital-web3-advisor/pull/12), encadeada e fora da `main`. Não inserir dados reais: acesso de clientes, piloto e produção não foram homologados. |
| [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) | Projeto prioritário da Agência Camaleão: pedidos guiados, triagem, versões textuais de entregas, aprovação ou pedido de ajustes e histórico por versão/hash. | Entregas A/B, demo guiada e orientações de briefing [integradas à main](https://github.com/ofelipepeixoto/camaleao-portal/blob/6acae7ad977cef31eef0d284a7bcffa40e9f20ba/README.md); homologação real, produção e integrações Supabase Auth/PostgREST/Storage e n8n pendentes. [Instruções da demo local](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/README.md#experimentar-com-dados-fictícios). [Abrir demonstração online](https://demo-portal.camaleaoweb3.com.br/) — somente dados fictícios locais no navegador; vídeo público pendente. |
| [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) | Projeto prioritário da Agência Camaleão: portal de infraestrutura de IA, do diagnóstico guiado à implantação e operação. | Em desenvolvimento. [Repositório público](https://github.com/ofelipepeixoto/camaleao-infra-portal) — código acessível para consulta. [Demonstração online](https://infra.camaleaoweb3.com.br/) — requer login com ChatGPT. |
| [Security Workbench](https://security-workbench.camaleaoweb3.com.br/) | Ferramenta de análise estática para repositórios GitHub autorizados: confere identidade, commit e hashes, apresenta candidatos com evidência para revisão humana e permite acompanhar relatórios e histórico. | [Demonstração pública](https://security-workbench.camaleaoweb3.com.br/) sem login e com dados fictícios: abra **Explorar exemplo** para testar o fluxo. A operação com análises reais permanece protegida por login ChatGPT; leitura limitada a repositórios públicos próprios e até 20 arquivos por análise. [Repositório privado](https://github.com/ofelipepeixoto/security-workbench) e [PR #8 em rascunho](https://github.com/ofelipepeixoto/security-workbench/pull/8) — código acessível somente a pessoas autorizadas, sem merge. |
| [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) | Jornada guiada para organizar evidências e avaliar o próximo experimento de uma oportunidade. | Aplicação experimental. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/radar-oaas/blob/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/CASE_STUDY.md). [Abrir demonstração](https://oaas.camaleaoweb3.com.br/). |
| [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) | Prévia de importação, triagem e análise de premissas para revisão humana. | MVP local em modo sombra, sem lances. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/CASE_STUDY.md). [Abrir demonstração](https://hermes.camaleaoweb3.com.br/). |
| [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia) | Ingestão de PDF, revisão por página e busca com referência ao original. | Laboratório local. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/CASE_STUDY.md). |

<details>
<summary>Ver as interfaces reais com dados fictícios</summary>

### Assistente Documental
![Busca com evidência no PDF fictício](https://raw.githubusercontent.com/ofelipepeixoto/assistente-documental-ia/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/demo.png)

### Radar OaaS
![Diagnóstico experimental do exemplo sintético](https://raw.githubusercontent.com/ofelipepeixoto/radar-oaas/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/demo.png)

### Hermes Leilão RJ
![Premissas financeiras do imóvel fictício em modo sombra](https://raw.githubusercontent.com/ofelipepeixoto/hermes-leilao-rj/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/demo.png)

</details>

### Capital Web3 Advisor — desenvolvimento atual

Cálculos de NAV, dívida, concentração, stress, perda impermanente (IL) e liquidez concentrada; aprovação, publicação por versão, downloads e revogação. O registro inicial da [PR #7](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/homologation.md) documenta navegador sintético e Supabase descartável em suítes separadas. A [CI dessa etapa](https://github.com/ofelipepeixoto/capital-web3-advisor/actions/runs/38108703715) testou o código de `dd0b539`; até o head `0ae8bcd`, mudaram apenas README e documentação.

O [portal de staging da PR #10](https://github.com/ofelipepeixoto/capital-web3-advisor/pull/10) já foi exercitado em Chromium com login, revisão por versão, publicação, negativas de acesso entre contas, download e revogação. A [CI aprovada](https://github.com/ofelipepeixoto/capital-web3-advisor/actions/runs/38157591368) usou Auth/PostgREST reais descartáveis, dados fictícios e uma ponte para o handler Node; os [limites documentados](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/d08d384a64416a687a9351632d77014f167c39f7/docs/authenticated-staging.md) incluem Deno Edge hospedado, TLS/CSP, MFA e produção ainda não validados. A PR #11 foi integrada somente à branch da #10; a #10 permanece aberta, sem integração à main. Edge hospedado e piloto real continuam pendentes.

OpenAI permanece em contratos com adapter fictício e consumo pago desativado; MCP é um exemplo local; templates n8n estão inativos. Sites e Hostinger seguem sem implantação. A validação descartável não libera produção nem certifica segurança. Sem custódia ou execução de transações. [Arquitetura](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/architecture.md) · [Backlog](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/backlog.md) · [PRs em revisão](https://github.com/ofelipepeixoto/capital-web3-advisor/pulls).

## Resultados e aprendizados

| Evidência reproduzida | Resultado observado | Limite da conclusão |
| --- | --- | --- |
| Capital Web3 — [validação inicial em suítes separadas](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/docs/homologation.md) | No [staging autenticado](https://github.com/ofelipepeixoto/capital-web3-advisor/actions/runs/38157591368), Chromium passou por login, revisão por versão, publicação, negativas entre contas, download e bloqueio de novos acessos após revogação. | Dados fictícios e Auth/PostgREST reais descartáveis via ponte Node. Não valida Deno Edge hospedado, TLS/CSP, MFA, produção ou resultado comercial; revogar não recupera arquivos já baixados. |
| Portal Camaleão — [versões e decisões B1/B2](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/docs/ENTREGA-B2.md) e [CI](https://github.com/ofelipepeixoto/camaleao-portal/actions/runs/38114158773) | Versões/decisões imutáveis no contrato SQL, conflitos sem aprovação automática e reenvios com o mesmo ID sem duplicar efeitos; datas preservadas entre SQL, driver, código de triagem e conclusão do job. | PostgreSQL descartável e navegador com fixtures; Auth/SDK simulados, sem execução real do n8n ou homologação Supabase Auth/PostgREST/Storage. A/B integradas à main; homologação real pendente, sem comprovação comercial. |
| PDF digital sintético de três páginas | 7/7 casos de busca; texto sem revisão permanece fora dos resultados. | Não mede OCR, documentos reais ou qualidade jurídica. |
| Radar OaaS — testes unitários/IA | 132 testes aprovados em seis arquivos. | Não comprova Auth/RLS real, uso por clientes ou retorno financeiro. |
| Hermes — domínio, importação e regressões selecionadas | 33 testes aprovados. | Não substitui suíte completa, homologação ou aprovação de investimento. |

Reproduções registradas em 11/10/2026 UTC; comandos, revisões de código e limites estão nos estudos de caso e registros de validação vinculados. Contagens de testes são evidências de comportamento no escopo executado, não métricas de produtividade ou adoção.

## Áreas de atuação

- Agentes de IA, automações e integração de ferramentas, APIs e contratos MCP com controles no servidor.
- Processamento de documentos, busca e respostas apoiadas em fontes (RAG).
- Revisão e publicação por versão, autorização por cliente e rastreabilidade de decisões.
- Testes reproduzíveis com dados fictícios, tratamento de falhas, conflitos e reenvios.
- Experimentação de modelos, políticas de orçamento e roteamento de tarefas.
- Desenvolvimento de produtos digitais para negócios, conteúdo e análise de oportunidades.
- Jornadas guiadas de pedidos e triagem, infraestrutura de IA e produtos white-label para a Agência Camaleão.
- Diagnósticos Web3/DeFi com cálculos determinísticos de risco.

## Tecnologias e ferramentas

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

Uso Vite no frontend do [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal/blob/3d2c321e4eeef06ed3c69aab9079a2995c794416/package.json); Vinext com [D1](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/db/index.ts) na implementação em revisão do [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/package.json); e Playwright nos testes de navegador do Portal e do [Capital Web3](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0ae8bcd76dee30130f896fbca8369d89b347b5ba/tests/browser/package.json). No Capital, OpenAI é contrato com adapter fictício, MCP é experimento local e n8n tem templates inativos; no Portal, a execução real do n8n continua pendente.

## Projetos e iniciativas

Desenvolvo o ecossistema Radar por etapas verificáveis. Os repositórios abaixo incluem produtos em desenvolvimento, bibliotecas experimentais e laboratórios; seus READMEs registram o que foi validado e os limites atuais.

### Integrações, evidências e modelos

- [Radar Integration Hub](https://github.com/ofelipepeixoto/radar-integration-hub) — laboratório de integrações governadas, ferramentas restritas e revisão humana; serviços externos ainda não homologados.
- [Radar Evidence Kit](https://github.com/ofelipepeixoto/radar-evidence-kit) — biblioteca experimental para contratos de evidência, recibos e proveniência.
- [Radar Model Router](https://github.com/ofelipepeixoto/radar-model-router) — experimentos locais de roteamento de tarefas e orçamento; sem chamadas a modelos. A [PR #6 em rascunho](https://github.com/ofelipepeixoto/radar-model-router/pull/6) propõe 216 exemplos sintéticos candidatos, todos não revisados por humanos, e [preparação offline para comparar modelo base e LoRA](https://github.com/ofelipepeixoto/radar-model-router/blob/fca479d1ce5b748d32a44ecd8806410816fbb6ab/experiments/ft05/README.md); treino e benchmark de modelos ainda não executados.

### Documentos e avaliação

- [Assistente documental](https://github.com/ofelipepeixoto/assistente-documental-ia) — ingestão local de PDFs, revisão por página e busca com fontes.
- [Avaliação de recuperação jurídica](https://github.com/ofelipepeixoto/avaliacao-rag-juridico) — avaliação de busca documental com contratos fictícios.
- [Laboratório de busca documental](https://github.com/ofelipepeixoto/laboratorio-busca-rag) — comparação de métodos de recuperação em conjuntos didáticos.
- [Agente com aprovação humana](https://github.com/ofelipepeixoto/agente-aprovacao-humana) — demonstração local de proposta, aprovação explícita e execução restrita.
- [Revisão de fontes](https://github.com/ofelipepeixoto/skill-revisao-de-fontes) — skill autoral para rastrear evidências e declarar incertezas.

### Produtos e iniciativas do ecossistema

- [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) — pedidos guiados e triagem para peças sociais, campanhas, sites e automações, com versões textuais, aprovação ou pedido de ajustes e histórico por versão/hash. Entregas A/B, demo guiada e orientações de briefing integradas à main; demo somente com dados fictícios locais, homologação real, produção e integrações Supabase Auth/PostgREST/Storage e n8n pendentes. É distinto do Camaleão Infra Portal, voltado a diagnóstico e operação de infraestrutura de IA.
- [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) — projeto prioritário em desenvolvimento da [Agência Camaleão](https://camaleaoweb3.com.br/); [repositório público](https://github.com/ofelipepeixoto/camaleao-infra-portal), código público e [demonstração online](https://infra.camaleaoweb3.com.br/) com login ChatGPT.
- [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) — console de consultores e entrega privada de diagnósticos com aprovação, publicação por versão e revogação; staging autenticado na PR #10, com Chromium → Auth/PostgREST reais descartáveis via ponte Node e dados fictícios. A PR #11 entrou apenas nessa branch, não na main. Edge hospedado, piloto real, demo pública e produção pendentes.
- [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) — avaliador experimental de prontidão para negócios orientados a resultados.
- [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) — triagem de oportunidades e organização de dossiês em modo sombra, com revisão humana e sem execução de lances.
- [Help Mídias](https://github.com/helpmidias-ia) · [Radar Tech News](https://github.com/radartech-news) · [Radar Disruptivo](https://radardisruptivo.com.br/) · [Agência Camaleão](https://camaleaoweb3.com.br/).

## Conteúdo e colaboração

Conecto análise editorial e desenvolvimento de produtos no [Radar Disruptivo](https://radardisruptivo.com.br/):

- [Agentes persistentes e governança](https://radardisruptivo.com.br/noticias/openai-dots-agentes-persistentes-governanca) — identidade, permissões, custos e responsabilidade humana.
- [MCP: segurança e governança](https://radardisruptivo.com.br/noticias/mcpa-certificacao-oficial-model-context-protocol) — contexto editorial para contratos e limites de ferramentas.

Esses artigos discutem o contexto do setor; não certificam nem validam as implementações dos meus projetos.

Os guias `CONTRIBUTING.md` propõem tarefas pequenas e verificáveis:

- [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/CONTRIBUTING.md): adicionar PDF fictício de duas colunas, registrar falhas de extração e executar `python avaliar_pdf.py --strict`, preservando os requisitos de aprovação.
- [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/27be19ee47e018337d4ca9778ffed71845561de1/CONTRIBUTING.md): adicionar CSVs fictícios com preços ausentes ou tipos de imóvel ambíguos, documentar a sinalização na prévia de importação e executar `npm run test:unit`.
- [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/a52d2a9b671f0cc952c5fa75eed3689071041679/CONTRIBUTING.md): melhorar um termo PT/EN e um exemplo fictício que diferencie dado desconhecido de evidência desfavorável; executar `npm run test:unit`.

Use fixtures reproduzíveis, resultado esperado explícito e registro dos limites e verificações. No Capital Web3 Advisor, siga o README, o backlog e as PRs em revisão. Ferramentas de IA apoiam o desenvolvimento; decisões de produto, revisão e limites permanecem explícitos.

## Onde me encontrar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Felipe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ofelipepeixoto/)
[![GitHub](https://img.shields.io/badge/GitHub-ofelipepeixoto-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ofelipepeixoto)
[![Radar Disruptivo](https://img.shields.io/badge/Site-Radar%20Disruptivo-176B45?style=for-the-badge)](https://radardisruptivo.com.br/)
[![Agência Camaleão](https://img.shields.io/badge/Site-Agência%20Camaleão-071007?style=for-the-badge&labelColor=176B45)](https://camaleaoweb3.com.br/)

## 📈 Estatísticas do GitHub

<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/stats.svg" alt="Estatísticas públicas do GitHub de Carlos Felipe" width="49%">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/top-langs.svg" alt="Linguagens dos repositórios públicos de Carlos Felipe" width="49%">
</p>

Atualizadas diariamente pelo GitHub Actions. As linguagens refletem a distribuição de código nos repositórios públicos, não nível de domínio ou horas de trabalho. As contribuições abaixo complementam a evolução da atividade.

## Minhas contribuições

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake.svg" alt="Animação de uma cobrinha percorrendo minhas contribuições no GitHub" width="100%">
  </picture>
</p>
