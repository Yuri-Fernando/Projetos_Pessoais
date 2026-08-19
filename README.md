# Projetos Pessoais

### AI Research · Agentic AI · SaaS · Intelligent Automation · Data Science · Open Source

Este repositório funciona como um **hub central dos meus projetos pessoais**, reunindo diferentes iniciativas desenvolvidas ao longo da minha trajetória em programação, dados, Inteligência Artificial, automação e desenvolvimento de produtos.

A organização é dividida em três grandes grupos:

## 1. Projetos de Terceiros e Estudos — Públicos

Reúne **submodules apontando para projetos da DIO, bootcamps, formações, comunidades e outros projetos externos**, utilizados para estudo, adaptação, experimentação e exploração técnica.

> **Nota técnica:** os itens desta categoria são referenciados via **Git Submodule apontando direto para o repositório original do autor**, fixado em um commit específico — não são forks no sentido do GitHub (não existe o badge "forked from" nem uma cópia própria do repositório). O histórico e a autoria originais ficam integralmente preservados. O mapa completo de cada submodule (pasta, repositório de origem e tipo) está na seção [Organização](#organização).

Entre os conteúdos estão projetos relacionados a:

- Python;
- Data Science;
- Machine Learning;
- Inteligência Artificial;
- IA Generativa;
- Automação;
- APIs;
- Cloud;
- Segurança;
- Engenharia de Software;
- Desenvolvimento de agentes.

Também fazem parte dessa categoria **submodules e adaptações de ferramentas e projetos externos**, utilizados como base para estudar arquiteturas, testar tecnologias, modificar funcionalidades e desenvolver integrações próprias.

### Evolution API

Um dos exemplos é a referência à **Evolution API** (submodule apontando direto para `EvolutionAPI/evolution-api`) como base para estudos e experimentações relacionados a WhatsApp e automação.

Os experimentos podem envolver:

- Integração com WhatsApp;
- Webhooks;
- APIs;
- n8n;
- AI Agents;
- CRM;
- Automação de atendimento;
- Gestão de leads;
- Memória contextual;
- Workflows comerciais.

### DIO — Lab Open Source

Submodule apontando para `digitalinnovationone/dio-lab-open-source`, repositório do lab **"Contribuindo em um Projeto Open Source no GitHub"** da Digital Innovation One, usado como registro de estudo e prática de contribuição open source.

### Case BI — Power BI Analyst

Submodule apontando para `julianazanelatto/power_bi_analyst`, fixado em um commit específico como referência de estudo de caso em análise de dados com Power BI. Mantido intocado — o pin não é atualizado automaticamente com o upstream.

Esses repositórios públicos têm principalmente caráter de **estudo, experimentação, extensão e integração**, mantendo a referência ao projeto original quando aplicável.

> Projetos de terceiros permanecem sujeitos às respectivas licenças e condições de uso. A presença de um submodule neste hub não implica autoria do projeto original — cada um mantém a atribuição ao autor/organização de origem.

---

## 2. Projetos Pessoais em Desenvolvimento e SaaS — Privados

Nesta categoria estão os projetos autorais que fazem parte da minha linha atual de **Pesquisa / P&D e desenvolvimento de produtos**, principalmente nas áreas de:

- Agentic AI;
- Multi-Agent Systems;
- AI Agents;
- n8n;
- CRM;
- Automação empresarial;
- Marketing Automation;
- RAG;
- SaaS;
- Financial Intelligence;
- Travel-Tech;
- Data Engineering;
- Sistemas proprietários de IA.

Entre as principais iniciativas estão projetos como:

- **ConectaAI** — SaaS de agentes de IA e central de serviços de IA para empresas;
- **JARVIS** — infraestrutura central de orquestração de IA e automação;
- **JhonesAI Ecosystem** — pesquisa em inteligência financeira, travel-tech e sistemas multiagente;
- **DDuas** — empresa em parceria de análise de dados e monitoramento para empresas, com o pipeline correspondente em **DDuas-Pipeline**;
- Outros produtos, agentes e infraestruturas em desenvolvimento.

> **Nota sobre a família ConectaAI:** por trás do nome existem três repositórios distintos, mantidos separados de propósito — `ConectaAI` (produto/SaaS público), `conectaAI_deploy` (repositório de deploy, privado) e `conecta-ai` (SaaS de agentes de IA para WhatsApp, privado). Os três estão referenciados como submodules independentes na seção [Organização](#organização).

Esses projetos podem envolver:

- Código proprietário;
- Dados confidenciais;
- Estratégias de negócio;
- Arquiteturas experimentais;
- Produtos SaaS;
- Infraestrutura interna;
- Componentes comerciais.

Por isso, muitos permanecem em **repositórios privados** e não são publicados neste hub.

---

## 3. Projetos Pequenos e Auxiliares — Públicos

Também fazem parte do ecossistema pequenos scripts, notebooks e ferramentas desenvolvidos para resolver problemas específicos, testar tecnologias ou servir como componentes auxiliares.

Exemplos:

- Análise de rede;
- Scripts Python;
- Automação de tarefas;
- Processamento de arquivos;
- NLP;
- Computer Vision;
- Experimentos de dados;
- Integrações;
- Utilitários de desenvolvimento;
- Notebooks experimentais.

Esses projetos representam principalmente **experimentação rápida e desenvolvimento de componentes**, podendo alguns deles evoluir posteriormente para iniciativas maiores.

---

## Objetivo deste Hub

A ideia deste repositório é funcionar como um **índice central dos diferentes projetos que compõem minha trajetória técnica**, mantendo separados os projetos externos, os projetos autorais e os experimentos menores.

```text
Terceiros / Estudos
       ↓
Experimentação
       ↓
Projetos Autorais
       ↓
Pesquisa / P&D
       ↓
SaaS / Produtos
       ↓
Infraestrutura de IA
```

Alguns projetos são independentes, enquanto outros fazem parte de iniciativas maiores e podem futuramente ser integrados a sistemas como **ConectaAI, JARVIS e outras infraestruturas do ecossistema**.

---

## Organização

Os projetos são mantidos em repositórios independentes e conectados a este hub por meio de **Git Submodules** — cada pasta abaixo é um repositório próprio, fixado em um commit específico.

```text
Projetos Pessoais
│
├── Terceiros / Estudos (submodule direto pro upstream, sem fork no GitHub)
│   ├── DIO
│   ├── Evolution API
│   ├── Case BI
│   └── Outros projetos externos
│
├── Projetos Autorais (submodule pro meu próprio repositório)
│   ├── AI
│   ├── Data
│   ├── Automation
│   ├── SaaS
│   └── Research
│
└── Projetos Pequenos (submodule pro meu próprio repositório)
    ├── Scripts
    ├── Notebooks
    └── Utilities
```

### Mapa de Submodules

| Pasta | Repositório | Tipo | Descrição |
|---|---|---|---|
| `evolution-api` | [EvolutionAPI/evolution-api](https://github.com/EvolutionAPI/evolution-api) | Terceiro — submodule direto (não é fork) | Evolution API — API open-source de integração com WhatsApp |
| `dio-lab-open-source` | [digitalinnovationone/dio-lab-open-source](https://github.com/digitalinnovationone/dio-lab-open-source) | Terceiro — submodule direto (não é fork) | Lab "Contribuindo em um Projeto Open Source no GitHub" da DIO |
| `power_bi_analyst` | [julianazanelatto/power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst) | Terceiro — submodule direto, **pin fixo intocado** (`b010c18`) | Case de estudo em análise de dados com Power BI |
| `ConectaAI` | [Dubbern/ConectaAI](https://github.com/Dubbern/ConectaAI) | Próprio — público | SaaS de agentes de IA |
| `conectaAI_deploy` | [Dubbern/conectaAI_deploy](https://github.com/Dubbern/conectaAI_deploy) | Próprio — privado, **intocado** | Repositório de deploy do ConectaAI |
| `conecta-ai` | [Dubbern/conecta-ai](https://github.com/Dubbern/conecta-ai) | Próprio — privado | SaaS de agentes de IA para WhatsApp |
| `Jarvis` | [Dubbern/Jarvis](https://github.com/Dubbern/Jarvis) | Próprio — público | Infraestrutura central de orquestração de IA e automação |
| `JhonesAI_Ecosystem` | [Dubbern/JhonesAI_Ecosystem](https://github.com/Dubbern/JhonesAI_Ecosystem) | Próprio — público | Multi-Agent Cognitive Investment & Travel & Financial Intelligence |
| `jhones-trader` | [Dubbern/jhones-trader](https://github.com/Dubbern/jhones-trader) | Próprio — privado | Sistema cognitivo de trading — 6 camadas, 30+ módulos Python |
| `DDuas` | [Dubbern/DDuas](https://github.com/Dubbern/DDuas) | Próprio — público | Empresa em parceria de análise de dados e monitoramento para empresas |
| `DDuas-Pipeline` | [Dubbern/DDuas-Pipeline](https://github.com/Dubbern/DDuas-Pipeline) | Próprio — privado | Pipeline de dados da DDuas |
| `BootcampSantander` | [Dubbern/BootcampSantander](https://github.com/Dubbern/BootcampSantander) | Próprio — público | Projetos do bootcamp Santander |
| `ocr` | [Dubbern/OCR](https://github.com/Dubbern/OCR) | Próprio — público | Projeto de OCR |
| `projetos_pequenos` | [Dubbern/Projetos_Pequenos](https://github.com/Dubbern/Projetos_Pequenos) | Próprio — público | Scripts e utilitários menores |
| `saas-atendimento-frame` | [Dubbern/saas-atendimento-frame](https://github.com/Dubbern/saas-atendimento-frame) | Próprio — privado, **intocado** | Base do SaaS Conecta v1 |
| `Case-Embarcados` | [Dubbern/Case-Embarcados](https://github.com/Dubbern/Case-Embarcados) | Próprio — privado, **intocado** | Primeiro case de teste em sistemas embarcados |

> Itens marcados **intocado** têm o pin do submodule mantido deliberadamente parado — não são atualizados automaticamente junto com os demais.

---

## Natureza dos Projetos

Os projetos deste ecossistema podem possuir diferentes estágios:

### 🟢 Concluído

Projetos finalizados e mantidos como portfólio, referência técnica ou registro acadêmico.

### 🔵 Pesquisa / P&D

Projetos experimentais ou de pesquisa aplicada, geralmente em evolução contínua.

### 🟡 Em Desenvolvimento

Produtos, SaaS, agentes e sistemas que continuam sendo construídos e evoluídos.

### ⚪ Arquivado

Projetos finalizados que permanecem como registro histórico da evolução técnica.

---

## Relação com Pesquisa e Desenvolvimento

Este hub também representa uma camada de organização da minha linha contínua de **Pesquisa e Desenvolvimento em IA, automação, dados e SaaS**.

A dinâmica é:

```text
Ideia
 ↓
Pesquisa
 ↓
Protótipo
 ↓
Experimentação
 ↓
Validação
 ↓
Projeto
 ↓
Produto / SaaS
```

Por isso, alguns projetos começam como pequenos experimentos, enquanto outros evoluem para infraestruturas maiores e proprietárias.

---

## Visão do Ecossistema

```text
                         Projetos Pessoais
                                │
          ┌─────────────────────┼─────────────────────┐
          ▼                     ▼                     ▼
      Open Source           Projetos Autorais      Experimentos
          │                     │                     │
          ▼                     ▼                     ▼
   Submodules / DIO        SaaS / IA / Data       Scripts / Labs
                                │
                   ┌────────────┼────────────┐
                   ▼            ▼            ▼
               ConectaAI      JARVIS     JhonesAI
                   │            │            │
                   └────────────┼────────────┘
                                ▼
                       Ecossistema de IA
```

---

## O que este repositório demonstra

- Organização de múltiplos projetos;
- Git Submodules;
- Arquitetura modular;
- Experimentação técnica;
- Pesquisa aplicada;
- Desenvolvimento de produtos;
- Agentic AI;
- SaaS;
- Data Science;
- Automação;
- Engenharia de Software;
- Integração de sistemas;
- Evolução de projetos independentes para um ecossistema integrado.

---

## Observação sobre Projetos de Terceiros

Os submodules de terceiros (DIO, Evolution API, Case BI) apontam diretamente para o repositório original do autor, fixados em um commit específico — não são forks no sentido do GitHub. São mantidos principalmente para:

- Estudo;
- Experimentação;
- Aprendizado;
- Adaptação;
- Integração;
- Testes de novas tecnologias;
- Exploração de arquiteturas existentes.

Quando um projeto externo é utilizado como base, a referência e a licença original devem ser preservadas conforme as condições definidas pelo projeto de origem.

---

## Status

🔵 **Pesquisa / P&D — Ecossistema em evolução contínua**

Este repositório funciona como o **hub central dos meus projetos pessoais e iniciativas de pesquisa e desenvolvimento**.

Novos projetos, experimentos, agentes, ferramentas e produtos SaaS podem ser adicionados continuamente por meio de novos repositórios e submodules.

A estrutura foi criada para acompanhar a evolução de uma coleção de projetos independentes para um **ecossistema integrado de IA, automação, dados e software**, mantendo públicos os projetos que podem ser compartilhados e privados aqueles que envolvem propriedade intelectual, dados confidenciais ou produtos em desenvolvimento.

---

## Autor

**Yuri Fernando Dubbern**

AI/ML Engineer · Agentic AI · SaaS · Intelligent Automation · Data Science · Research & Development

[LinkedIn](https://www.linkedin.com/in/yuridubbern) · [GitHub](https://github.com/Yuri-Fernando) · [Lattes](http://lattes.cnpq.br/7151392692642166) · [Linktree](https://linktr.ee/yuri.f.dubbern)
