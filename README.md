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
| [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) | Projeto prioritário: cálculos determinísticos de risco DeFi, console de consultores e portal privado de diagnósticos com revisão humana. | Em desenvolvimento ativo; testes locais com dados fictícios. [Instruções para testar](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0b5cf876f20590507e80facb3f6a58092860c9a9/README.md). Demo visual pendente. |
| [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) | Projeto prioritário da Agência Camaleão: pedidos guiados de clientes, acompanhamento e triagem da equipe. | Entrega A em revisão; sem produção ou integração Supabase/n8n homologada. [Instruções da demo local](https://github.com/ofelipepeixoto/camaleao-portal#experimentar-com-dados-fictícios); vídeo público pendente. |
| [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) | Projeto prioritário da Agência Camaleão: portal de infraestrutura de IA, do diagnóstico guiado à implantação e operação. | Em desenvolvimento. [Repositório público](https://github.com/ofelipepeixoto/camaleao-infra-portal) — código acessível para consulta. [Demonstração online](https://infra.camaleaoweb3.com.br/) — requer login com ChatGPT. |
| [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia) | Ingestão de PDF, revisão por página e busca com referência ao original. | Laboratório local. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/CASE_STUDY.md). |
| [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) | Jornada guiada para organizar evidências e avaliar o próximo experimento de uma oportunidade. | Aplicação experimental. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/radar-oaas/blob/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/CASE_STUDY.md). [Abrir demonstração](https://radar-oaas.radarjacarepagua.chatgpt.site/). |
| [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) | Prévia de importação, triagem e análise de premissas para revisão humana. | MVP local em modo sombra, sem lances. [Estudo de caso e vídeo](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/CASE_STUDY.md). [Abrir demonstração](https://hermes-leilao-rj.radarjacarepagua.chatgpt.site/). |

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

Cálculos de NAV, dívida, concentração, stress, perda impermanente (IL) e liquidez concentrada; revisão, publicação por versão, downloads e revogação. [Validação registrada](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0b5cf876f20590507e80facb3f6a58092860c9a9/docs/testing.md): 68 testes Python e dois cenários JavaScript. São testes locais sintéticos; a validação visual em navegador permanece pendente.

Contratos OpenAI, MCP local, templates n8n inativos e preparação Supabase estão disponíveis. Supabase real, OpenAI paga, n8n, Sites e Hostinger ainda não foram implantados ou homologados. Sem custódia ou execução de transações. [Arquitetura](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0b5cf876f20590507e80facb3f6a58092860c9a9/docs/architecture.md) · [Backlog](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/0b5cf876f20590507e80facb3f6a58092860c9a9/docs/backlog.md) · [PRs em revisão](https://github.com/ofelipepeixoto/capital-web3-advisor/pulls).

## Resultados e aprendizados

| Evidência reproduzida | Resultado observado | Limite da conclusão |
| --- | --- | --- |
| PDF digital sintético de três páginas | 7/7 casos de busca; texto sem revisão permanece fora dos resultados. | Não mede OCR, documentos reais ou qualidade jurídica. |
| Radar OaaS — testes unitários/IA | 132 testes aprovados em seis arquivos. | Não comprova Auth/RLS real, uso por clientes ou retorno financeiro. |
| Hermes — domínio, importação e regressões selecionadas | 33 testes aprovados. | Não substitui suíte completa, homologação ou aprovação de investimento. |

Reprodução em 11/10/2026 UTC; comandos, revisões de código e limites estão nos estudos de caso. Contagens de testes são evidências de comportamento no escopo executado, não métricas de produtividade ou adoção.

## Áreas de atuação

- Engenharia de agentes de IA e automações com revisão humana.
- Integração de ferramentas, APIs e contratos MCP com controles no servidor.
- Processamento de documentos, busca e respostas apoiadas em fontes (RAG).
- Rastreabilidade de evidências, avaliações reproduzíveis e tratamento de falhas.
- Experimentação de modelos, políticas de orçamento e roteamento de tarefas.
- Desenvolvimento de produtos digitais para negócios, conteúdo e análise de oportunidades.
- Jornadas guiadas de clientes, acompanhamento de pedidos e triagem para a Agência Camaleão.
- Desenvolvimento de infraestrutura de IA e produtos white-label para a Agência Camaleão.
- Produtos de diagnóstico Web3/DeFi com cálculos determinísticos de risco e revisão humana.

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

## Projetos e iniciativas

Desenvolvo o ecossistema Radar por etapas verificáveis. Os repositórios abaixo incluem produtos em desenvolvimento, bibliotecas experimentais e laboratórios; seus READMEs registram o que foi validado e os limites atuais.

### Integrações, evidências e modelos

- [Radar Integration Hub](https://github.com/ofelipepeixoto/radar-integration-hub) — laboratório de integrações governadas, ferramentas restritas e revisão humana; serviços externos ainda não homologados.
- [Radar Evidence Kit](https://github.com/ofelipepeixoto/radar-evidence-kit) — biblioteca experimental para contratos de evidência, recibos e proveniência.
- [Radar Model Router](https://github.com/ofelipepeixoto/radar-model-router) — experimentos locais de roteamento de tarefas e orçamento; sem chamadas a modelos.

### Documentos e avaliação

- [Assistente documental](https://github.com/ofelipepeixoto/assistente-documental-ia) — ingestão local de PDFs, revisão por página e busca com fontes.
- [Avaliação de recuperação jurídica](https://github.com/ofelipepeixoto/avaliacao-rag-juridico) — avaliação de busca documental com contratos fictícios.
- [Laboratório de busca documental](https://github.com/ofelipepeixoto/laboratorio-busca-rag) — comparação de métodos de recuperação em conjuntos didáticos.
- [Agente com aprovação humana](https://github.com/ofelipepeixoto/agente-aprovacao-humana) — demonstração local de proposta, aprovação explícita e execução restrita.
- [Revisão de fontes](https://github.com/ofelipepeixoto/skill-revisao-de-fontes) — skill autoral para rastrear evidências e declarar incertezas.

### Produtos e iniciativas do ecossistema

- [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) — portal de pedidos e triagem para peças sociais, campanhas, sites e automações; entrega A em revisão. É distinto do Camaleão Infra Portal, voltado a diagnóstico e operação de infraestrutura de IA.
- [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) — projeto prioritário em desenvolvimento da [Agência Camaleão](https://camaleaoweb3.com.br/); [repositório público](https://github.com/ofelipepeixoto/camaleao-infra-portal), código público e [demonstração online](https://infra.camaleaoweb3.com.br/) com login ChatGPT.
- [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) — projeto prioritário em desenvolvimento ativo: console local de consultores e entrega privada de diagnósticos revisados; dados fictícios e integrações de produção pendentes.
- [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) — avaliador experimental de prontidão para negócios orientados a resultados.
- [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) — triagem de oportunidades e organização de dossiês em modo sombra, com revisão humana e sem execução de lances.
- [Help Mídias](https://github.com/helpmidias-ia) · [Radar Tech News](https://github.com/radartech-news) · [Radar Disruptivo](https://radardisruptivo.com.br/) · [Agência Camaleão](https://camaleaoweb3.com.br/).

## Conteúdo e colaboração

Conecto análise editorial e desenvolvimento de produtos no [Radar Disruptivo](https://radardisruptivo.com.br/):

- [Agentes persistentes e governança](https://radardisruptivo.com.br/noticias/openai-dots-agentes-persistentes-governanca) — identidade, permissões, custos e responsabilidade humana.
- [MCP: segurança e governança](https://radardisruptivo.com.br/noticias/mcpa-certificacao-oficial-model-context-protocol) — contexto editorial para contratos e limites de ferramentas.

Esses artigos discutem o contexto do setor; não certificam nem validam as implementações dos meus projetos.

Para colaborar, consulte `CONTRIBUTING.md` no Assistente Documental, Radar OaaS e Hermes; no Capital Web3 Advisor, siga o README, o backlog e as PRs em revisão: exemplos fictícios, propostas pequenas, critérios de aceite e verificações reproduzíveis. Ferramentas de IA apoiam o desenvolvimento; decisões de produto, revisão e limites permanecem explícitos.

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
