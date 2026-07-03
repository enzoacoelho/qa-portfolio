# Portfólio de Engenharia de Qualidade

[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)](https://github.com/seu-usuario)
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)](https://github.com/seu-usuario)
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)](https://github.com/seu-usuario)
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)](https://github.com/seu-usuario)
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)](https://github.com/seu-usuario)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)](https://github.com/seu-usuario)
[![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/seu-usuario)

Este repositório reúne meus projetos práticos em Engenharia de Qualidade de Software, organizados para apresentar minha evolução de forma clara e objetiva.

Aqui estão concentrados trabalhos que envolvem testes manuais, automação web e mobile, APIs, unidade, performance, containers, integração contínua e uso de IA aplicada à qualidade — sempre baseados em cenários próximos à realidade de aplicações de mercado.

## Objetivo do portfólio

- Demonstrar minha experiência prática em qualidade de software
- Apresentar projetos desenvolvidos ao longo dos meus estudos
- Mostrar a aplicação de boas práticas de testes, automação e organização
- Evidenciar minha capacidade de analisar contexto, definir estratégia e tomar decisões técnicas

Mais do que listar ferramentas, este portfólio busca mostrar como eu penso em qualidade.

## Destaques 
Projetos que melhor representam minha forma de trabalhar e tomar decisões técnicas:

- **[`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp)** — E2E com Cypress cobrindo autenticação, gerenciamento de conta, transações de pagamento/cobrança, feed com filtros e notificações. Arquitetura em Page Objects, com Components para elementos reutilizados entre abas e Commands para ações genéricas.
- **[`pw-streaming`](https://github.com/enzoacoelho/pw-streaming)** — E2E com Playwright numa plataforma de streaming (login, leads, catálogo de filmes e séries). Classes de ação injetadas via `test.extend`, com integração direta a banco PostgreSQL e chamadas de API para setup de cenários.
- **[`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura)** — API ponta a ponta de um sistema de biblioteca, com permissões diferenciadas (usuário comum/admin), requests organizados por endpoint e pipeline de CI no GitHub Actions publicando relatório Allure.

## Estrutura do portfólio

```
├── Projetos
│   ├── Testes Manuais e Estratégias
│   ├── Testes de Unidade
│   ├── Automação Web (UI)
│   ├── Automação de API
│   ├── UI Avançado
│   ├── Automação Mobile
│   ├── Testes de Performance
│   ├── Containers (Docker)
│   ├── CI/CD e Qualidade Contínua
│   └── Engenharia de Inteligência Artificial
├── Desafios práticos
├── Boas práticas adotadas
└── Considerações finais
```

## Projetos

Abaixo estão os principais projetos que fazem parte deste portfólio. Cada projeto possui seu próprio repositório e um README com a explicação do contexto, objetivo, estratégia de testes e instruções de execução.

### 1. Testes Manuais e Estratégias

QA manual sobre uma aplicação Todo List (criação, edição, conclusão de tarefas, filtros e contador de itens ativos), com testes funcionais, exploratórios e de edge case gerenciados no Jira/Zephyr Scale — incluindo bugs reais como o contador de itens ativos calculando errado e a possibilidade de criar tarefas vazias colando espaços em branco.

**Tecnologias:** Jira Cloud, Zephyr Scale
**Repositório:** [`qa-manual-todo-list`](https://github.com/enzoacoelho/qa-manual-todo-list)

### 2. Testes de Unidade

Exemplos de testes aplicados a funções e regras de negócio isoladas, com foco em confiabilidade e manutenção do código.

**Tecnologias utilizadas:**
- JavaScript
- Jest
- Java
- JUnit

**Repositórios:**
- [`jest-logic-challenges`](https://github.com/enzoacoelho/jest-logic-challenges) — Exercícios de lógica em JS, focados em cobertura de casos-limite.
- [`jest-logic-users`](https://github.com/enzoacoelho/jest-logic-users) — Testes unitários aplicados a regras isoladas de negócio.
- [`junit-banksystem`](https://github.com/enzoacoelho/junit-banksystem) — Sistema bancário em Java com JUnit, validando regras críticas como saldo e transações.

### 3. Automação Web (UI)

Testes end-to-end (E2E) simulando a jornada real do usuário em aplicações web.

**Tecnologias utilizadas:**
- Cypress
- Playwright
- JavaScript / TypeScript
- NPM

**Repositórios:**
- [`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp) — E2E cobrindo autenticação, gerenciamento de conta, transações de pagamento/cobrança, feed com filtros e notificações. Arquitetura em Page Objects, com Components para elementos reutilizados entre abas e Commands para ações genéricas.
- [`pw-streaming`](https://github.com/enzoacoelho/pw-streaming) — E2E numa plataforma de streaming (login, leads, catálogo de filmes e séries). Classes de ação injetadas via `test.extend`, com integração direta a banco PostgreSQL e chamadas de API para setup de cenários.

### 4. Automação de API

Validações de regras de negócio, testes funcionais e de contrato diretamente na camada de serviços.

**Tecnologias utilizadas:**
- Playwright
- Cypress
- Testes de API REST

**Repositórios:**
- [`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura) — Validação de regras de negócio e cenários positivos/negativos da API do Hub de Leitura.
- [`pw-api-shortbeyond`](https://github.com/enzoacoelho/pw-api-shortbeyond) — Testes de contrato e cenários funcionais via Playwright.

### 5. UI Avançado

Cenários complexos de interface que exigem controle sobre o comportamento assíncrono e regras de negócio guiadas por comportamento.

**Tecnologias utilizadas:**
- Cypress
- Cucumber / Gherkin
- Mocking HTTP (`cy.intercept`)

**Repositórios:**
- [`cy-cucumber-hubleitura`](https://github.com/enzoacoelho/cy-cucumber-hubleitura) — BDD ligando cenários de negócio escritos em Gherkin à automação técnica.
- [`cy-intercept-appactions`](https://github.com/enzoacoelho/cy-intercept-appactions) — Mock de dados e controle de rede para simular cenários difíceis de reproduzir (erros de API, latência, respostas inesperadas).

### 6. Automação Mobile

Testes em aplicações nativas e híbridas para dispositivos móveis.

**Tecnologias utilizadas:**
- Appium
- WebDriverIO
- Robot Framework

**Repositórios:**
- [`appium-wdio`](https://github.com/seu-usuario/appium-wdio) — Automação Android com Appium e WebDriverIO.
- [`udemy-appium`](https://github.com/seu-usuario/udemy-appium) — Automação mobile estruturada com Robot Framework.

### 7. Testes de Performance

Avaliação de riscos, comportamento sob carga, estresse e mapeamento de gargalos.

**Tecnologias utilizadas:**
- k6
- Apache JMeter

**Repositórios:**
- [`k6-tests`](https://github.com/seu-usuario/k6-tests) — Scripts modernos de carga com análise de métricas (latência, taxa de erro, throughput).
- [`jmeter-blazedemo`](https://github.com/seu-usuario/jmeter-blazedemo) — Plano de testes estruturado em JMeter sobre a aplicação BlazeDemo.

### 8. Containers (Docker)

Criação e isolamento de ambientes para garantir a reprodutibilidade dos testes.

**Tecnologias utilizadas:**
- Docker
- Docker Compose

**Repositórios:**
- [`react-express`](https://github.com/seu-usuario/react-express) — Containerização de aplicação React + API Express, isolando frontend e backend.
- [`cy-interception-docker`](https://github.com/seu-usuario/cy-interception-docker) — Execução de testes Cypress em modo headless dentro de containers, garantindo ambiente reprodutível.

### 9. CI/CD e Qualidade Contínua

Integração de testes automatizados em esteiras de deploy, aplicando o conceito de Shift-Left Testing ao longo do fluxo de entrega.

**Tecnologias utilizadas:**
- GitHub Actions
- Jenkins

**Repositórios:**
- [`gitactions-serverest`](https://github.com/seu-usuario/gitactions-serverest) — Pipeline de testes automatizados com GitHub Actions sobre a API ServeRest.
- [`jenkins-hub-de-leitura`](https://github.com/seu-usuario/jenkins-hub-de-leitura) — Pipeline Jenkins integrando testes automatizados do projeto Hub de Leitura.

### 10. Engenharia de Inteligência Artificial

Exploração de inteligências artificiais generativas para acelerar e garantir eficiência na escrita de testes.

**Tecnologias utilizadas:**
- LLMs
- Prompts estruturados para QA

**Repositórios:**
- [`ia-tests`](https://github.com/seu-usuario/ia-tests) — Engenharia de prompts para geração de cenários de teste.
- [`ia-tests-analise`](https://github.com/seu-usuario/ia-tests-analise) — Análise preditiva de métricas de qualidade com apoio de IA.

## Desafios práticos

Além dos projetos completos, este portfólio também inclui desafios práticos voltados para o exercício de habilidades específicas.

Os desafios têm como foco:

- raciocínio de testes
- organização
- tomada de decisão
- aplicação de boas práticas
- estratégia de testes voltada para automação
- testes baseados em risco

Cada desafio descreve claramente o problema, o objetivo e o entregável esperado.

## Boas práticas adotadas

Ao longo dos projetos, busquei aplicar práticas como:

- organização clara de pastas e arquivos
- uso adequado de `.gitignore`
- READMEs explicando contexto e objetivo
- código simples, legível e sustentável
- foco em manutenção e clareza

## Considerações finais

Essa jornada começou nos testes manuais, priorizando cenários por risco, e foi crescendo em direção à automação web, API, mobile, performance e integração contínua. O maior desafio técnico até aqui foi migrar e adaptar projetos existentes (como o `cypress-rwa`) para um novo ambiente sem perder cobertura de testes — isso me ensinou a olhar para automação não só como "escrever testes", mas como manter um sistema de qualidade sustentável ao longo do tempo.

Os próximos passos que pretendo explorar: testes de contrato mais aprofundados, observabilidade aplicada à qualidade, e ampliar o uso de IA generativa para análise preditiva de falhas em pipelines de CI/CD.

Se quiser conversar sobre qualquer um desses projetos ou sobre minha forma de pensar em qualidade, fique à vontade para entrar em contato.
