<p align="center">
  <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/main/banner.png" alt="Banner de Carlos Felipe — engenharia de IA" width="100%">
</p>

<h1 align="center">Carlos Felipe</h1>
<p align="center"><strong>Português</strong> · <a href="README_EN.md">English</a></p>

Construo produtos digitais e experimentos de IA para organizar evidências, orientar decisões e tornar fluxos de trabalho mais claros para equipes e clientes. Trabalho da definição do problema à implementação e à revisão humana, com atenção ao que foi realmente testado. O portfólio reúne iniciativas em automação, conteúdo, infraestrutura e Web3 em estágios diferentes.

## Projetos em destaque

| Projeto | Problema, solução e contribuição | Estágio e como conhecer |
| --- | --- | --- |
| [Capital Web3 Advisor](https://github.com/ofelipepeixoto/capital-web3-advisor) | Uma consultoria DeFi precisa calcular riscos e entregar diagnósticos revisados sem executar transações. Desenvolvo o motor determinístico, o console de revisão e um portal de entrega por versão. | Demonstração local com dados fictícios; a camada de [staging autenticado está na PR #10](https://github.com/ofelipepeixoto/capital-web3-advisor/pull/10), encadeada sobre outras PRs e ainda fora da `main`. O [registro de validação](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/d08d384a64416a687a9351632d77014f167c39f7/docs/authenticated-staging.md) distingue Auth/PostgREST descartáveis de Edge hospedado e piloto real, ainda pendentes. |
| [Camaleão Infra Portal](https://github.com/ofelipepeixoto/camaleao-infra-portal) | Necessidades de infraestrutura de IA exigem diagnóstico, plano revisado e acompanhamento. Estruturo o produto da Agência Camaleão e sua jornada de revisão. | A [`main` contém plano e referência offline](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/71f9102792ac2a4e7b6156a85f24d9e4636bb4f7/README.md); a implementação de intake persistente e revisão está em [PRs encadeadas](https://github.com/ofelipepeixoto/camaleao-infra-portal/pulls). CI nas branches não comprova implantação nem homologação de clientes. |
| [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal) | Pedidos de peças, campanhas, sites e automações perdem contexto nas trocas. Desenvolvi uma jornada de briefing, triagem, versões textuais e decisão de aprovação ou ajustes. É um produto distinto do portal de infraestrutura. | Entregas A/B e revisão guiada [integradas à `main`](https://github.com/ofelipepeixoto/camaleao-portal/commits/main/). [Instruções da demo local com dados fictícios](https://github.com/ofelipepeixoto/camaleao-portal/blob/6acae7ad977cef31eef0d284a7bcffa40e9f20ba/README.md#experimentar-com-dados-fict%C3%ADcios); Supabase Auth/PostgREST/Storage, n8n e operação real ainda carecem de homologação. |
| [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas) | Fundadores precisam saber qual evidência falta antes de avançar em uma oportunidade. Construí uma avaliação guiada que separa dados ausentes, regras e revisão humana. | Aplicação experimental na `main`. [Estudo de caso, captura e vídeo com exemplo sintético](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/docs/portfolio/CASE_STUDY.md); sem validação de adoção ou resultado financeiro. |
| [Hermes Leilão RJ](https://github.com/ofelipepeixoto/hermes-leilao-rj) | A análise de imóveis em leilão requer conferir origem, importação e premissas antes de decidir. Construí prévia de importação, triagem e dossiê com campos pendentes visíveis. | MVP local em modo sombra, sem lances. [Estudo de caso, captura e vídeo fictícios](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/docs/portfolio/CASE_STUDY.md); não é recomendação de investimento. |
| [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia) | Buscar em PDFs sem perder a referência original exige conferir cada página. Construí ingestão, correção e aprovação de trechos antes da busca com fontes. | Laboratório local. [Estudo de caso, captura e vídeo com PDF fictício](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/docs/portfolio/CASE_STUDY.md); documentos reais e OCR não foram homologados. |

<details>
<summary>Ver interfaces executadas com dados fictícios</summary>

### Assistente Documental
![Busca com evidência no PDF fictício](https://raw.githubusercontent.com/ofelipepeixoto/assistente-documental-ia/3f02c535d255a1e497ccdf4c23f26ac6dcb4eb03/docs/portfolio/demo.png)

### Radar OaaS
![Diagnóstico experimental do exemplo sintético](https://raw.githubusercontent.com/ofelipepeixoto/radar-oaas/a52d2a9b671f0cc952c5fa75eed3689071041679/docs/portfolio/demo.png)

### Hermes Leilão RJ
![Premissas financeiras do imóvel fictício em modo sombra](https://raw.githubusercontent.com/ofelipepeixoto/hermes-leilao-rj/27be19ee47e018337d4ca9778ffed71845561de1/docs/portfolio/demo.png)

</details>

## Resultados e aprendizados

- **Revisão por versão:** no [Capital Web3](https://github.com/ofelipepeixoto/capital-web3-advisor/blob/d08d384a64416a687a9351632d77014f167c39f7/docs/authenticated-staging.md), o fluxo Chromium da CI cobriu login, revisão, publicação, negativas entre contas, download e revogação com dados fictícios e Auth/PostgREST descartáveis por uma ponte Node. Edge hospedado, MFA, TLS/CSP e piloto real continuam pendentes; revogar acesso não recupera um arquivo já baixado.
- **Conflitos e reenvios:** o [Portal Camaleão](https://github.com/ofelipepeixoto/camaleao-portal/blob/6acae7ad977cef31eef0d284a7bcffa40e9f20ba/docs/ENTREGA-B2.md) preserva decisões por versão e trata reenvios sem duplicar efeitos nos testes de banco. Fixtures de navegador e banco descartável não substituem a homologação das integrações reais.
- **Incerteza visível:** [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/docs/portfolio/CASE_STUDY.md) mantém evidência insuficiente como pendência; [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/docs/portfolio/CASE_STUDY.md) conserva campos financeiros desconhecidos; o [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/docs/portfolio/CASE_STUDY.md) exclui texto não aprovado da busca. Os estudos usam dados fictícios e não medem adoção, eficácia em clientes ou receita.

## Áreas de atuação

- Produtos com agentes e automações, ferramentas limitadas, aprovação humana e falhas explícitas.
- Processamento e busca documental com fonte, versão e avaliação de recuperação.
- Experimentos de modelos, roteamento de tarefas e controle de orçamento.
- Jornadas digitais de pedidos, diagnóstico e conteúdo editorial.
- Análise de risco Web3/DeFi e triagem de oportunidades sem execução financeira.

## Tecnologias e ferramentas

Uso **Python** para motores determinísticos e laboratórios documentais; **TypeScript, Vite e Playwright** no Portal Camaleão; **Astro e React** no Radar OaaS; **PostgreSQL e contratos Supabase** nos testes de autorização e persistência. A implementação em revisão do Infra Portal usa **Vinext e D1** ([código](https://github.com/ofelipepeixoto/camaleao-infra-portal/blob/a000d53d7d7495e1c4114e3cac0544d017bb3e85/apps/site/db/index.ts)). **n8n** aparece em contratos e templates inativos nos projetos citados; **MCP** em exemplos locais; no Capital, **OpenAI** permanece com adapter fictício e consumo pago desativado. Essas menções descrevem usos concretos, sem afirmar integrações em produção.

## Projetos e iniciativas

**Integrações e evidências.** [Radar Integration Hub](https://github.com/ofelipepeixoto/radar-integration-hub) estuda ferramentas governadas com demonstrações locais; [Radar Evidence Kit](https://github.com/ofelipepeixoto/radar-evidence-kit) desenvolve contratos experimentais de evidência, recibos e proveniência. As integrações externas seguem limitadas ao escopo documentado em cada repositório.

**Modelos e aprendizagem.** [Radar Model Router](https://github.com/ofelipepeixoto/radar-model-router) recomenda localmente níveis de modelo e orçamento, sem chamar modelos; reconhece a política de terceiro usada como referência em seus avisos. As [PRs FT05](https://github.com/ofelipepeixoto/radar-model-router/pulls) preparam corpus sintético e avaliação, sem treino ou benchmark completo comprovado. [Radar Classificador Colab](https://github.com/ofelipepeixoto/radar-classificador-colab) é uma extração educacional em [PRs rascunho](https://github.com/ofelipepeixoto/radar-classificador-colab/pulls); ainda não é tutorial homologado nem modelo para atendimento real.

**Documentos e revisão.** [Avaliação de recuperação jurídica](https://github.com/ofelipepeixoto/avaliacao-rag-juridico) usa contratos fictícios; [Laboratório de busca RAG](https://github.com/ofelipepeixoto/laboratorio-busca-rag) compara métodos de recuperação; [Agente com aprovação humana](https://github.com/ofelipepeixoto/agente-aprovacao-humana) demonstra execução restrita após confirmação; [Revisão de fontes](https://github.com/ofelipepeixoto/skill-revisao-de-fontes) organiza evidências e incertezas.

**Ecossistema e conteúdo.** [Radar Tech News](https://github.com/radartech-news), [Help Mídias](https://github.com/helpmidias-ia), [Radar Disruptivo](https://radardisruptivo.com.br/) e [Agência Camaleão](https://camaleaoweb3.com.br/) são iniciativas do ecossistema; os portais Camaleão acima atendem jornadas distintas dentro da mesma agência.

## Conteúdo e colaboração

No [Radar Disruptivo](https://radardisruptivo.com.br/), conecto análise editorial e decisões de produto. Leia os textos sobre [agentes persistentes e governança](https://radardisruptivo.com.br/noticias/openai-dots-agentes-persistentes-governanca) e [MCP, segurança e governança](https://radardisruptivo.com.br/noticias/mcpa-certificacao-oficial-model-context-protocol). Os artigos oferecem contexto, não certificam os projetos.

Para conhecer o trabalho, comece pelos estudos de caso e vídeos dos destaques. Para contribuir com exemplos fictícios e verificações reproduzíveis, veja os guias do [Assistente Documental](https://github.com/ofelipepeixoto/assistente-documental-ia/blob/83d489854a53032ecbf6291c0f2a200efb536a78/CONTRIBUTING.md), [Hermes](https://github.com/ofelipepeixoto/hermes-leilao-rj/blob/3cc0a7c1162decdb5118032e57c98635db7615e5/CONTRIBUTING.md) e [Radar OaaS](https://github.com/ofelipepeixoto/radar-oaas/blob/aceb046431fa199222f72fb2091c0b63a992102f/CONTRIBUTING.md).

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

Atualizadas diariamente pelo GitHub Actions. A distribuição de linguagens reflete código público, não domínio técnico ou horas de trabalho; o perfil e alguns repositórios importados/de referência são excluídos do cartão de linguagens.

## Minhas contribuições

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/ofelipepeixoto/ofelipepeixoto/output/github-contribution-grid-snake.svg" alt="Animação de uma cobrinha percorrendo minhas contribuições no GitHub" width="100%">
  </picture>
</p>
