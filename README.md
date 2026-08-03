# Portfólio de Engenharia de Qualidade

[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)]
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)]
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)]
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)]
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)]
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)]
[![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)]

## Sobre Mim
Fui desenvolvedor por 4 anos e atualmente estou em transição de carreira para Qualidade de Software. Essa bagagem técnica me ajuda a ler código de teste com mais profundidade, entender arquitetura de aplicações e conversar de igual para igual com times de desenvolvimento — algo que uso a favor da automação e não só da execução de testes.

Este repositório reúne meus projetos práticos em Engenharia de Qualidade, envolvendo testes manuais, automação web e mobile, APIs, testes de unidade, performance, containers e integração contínua, sempre baseados em cenários próximos à realidade de aplicações de mercado.

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

´´Os READMEs individuais desses três projetos trazem contexto completo, estratégia de testes e evidências (prints, relatórios, bugs encontrados).´´

## Demais projetos de prática

Repositórios complementares, desenvolvidos ao longo dos estudos para praticar ferramentas e conceitos específicos.

### 1. Testes Manuais e Estratégias
*   [`qa-manual-todo-list`](https://github.com/enzoacoelho/qa-manual-todo-list) — QA manual sobre uma aplicação Todo List com testes funcionais, exploratórios e de edge case gerenciados no Jira/Zephyr Scale (incluindo mapeamento de bugs reais de lógica).
    *   *Tecnologias:* Jira Cloud, Zephyr Scale
 
### 2. Automação Web (UI e Práticas Avançadas)
*   [`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp) — E2E cobrindo autenticação, gerenciamento de conta, transações e notificações. Arquitetura em Page Objects, Components e Commands.
*   [`pw-streaming`](https://github.com/enzoacoelho/pw-streaming) — E2E em plataforma de streaming com classes injetadas via `test.extend`, integração a banco PostgreSQL e chamadas de API.
*   [`cy-cucumber-hubleitura`](https://github.com/enzoacoelho/cy-cucumber-hubleitura) — Desenvolvimento guiado por comportamento (BDD) vinculando cenários escritos em Gherkin à automação técnica.
    *   *Tecnologias:* Cypress, Playwright, Cucumber / Gherkin, JavaScript, NPM
 
### 3. Automação Mobile
*   [`appium-wdio`](https://github.com/enzoacoelho/appium-wdio) — Automação Android com Appium e WebDriverIO.
*   [`udemy-appium`](https://github.com/enzoacoelho/udemy-appium) — Automação mobile estruturada com Robot Framework.
    *   *Tecnologias:* Appium, WebDriverIO, Robot Framework
 
### 4. Automação de API
*   [`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura) — Validação de regras de negócio e cenários positivos/negativos da API do Hub de Leitura.
*   [`pw-api-shortbeyond`](https://github.com/enzoacoelho/pw-api-shortbeyond) — Testes de contrato e cenários funcionais via Playwright.
    *   *Tecnologias:* Playwright, Cypress, Testes de API REST
 
### 5. Testes de Performance
*   [`k6-tests`](https://github.com/enzoacoelho/k6-tests) — Scripts modernos de carga com análise de métricas (latência, taxa de erro, throughput).
*   [`jmeter-blazedemo`](https://github.com/enzoacoelho/jmeter-blazedemo) — Plano de testes estruturado em JMeter sobre a aplicação BlazeDemo.
    *   *Tecnologias:* k6, Apache JMeter

### 6. Testes de Unidade
*   [`jest-logic-challenges`](https://github.com/enzoacoelho/jest-logic-challenges) — Exercícios de lógica em JS, focados em cobertura de casos-limite.
*   [`junit-banksystem`](https://github.com/enzoacoelho/junit-banksystem) — Sistema bancário em Java com JUnit, validando regras críticas como saldo e transações.
    *   *Tecnologias:* JavaScript, Jest, Java, JUnit

### 7. DevOps e Infraestrutura de Testes (CI/CD & Containers)
*   [`gitactions-serverest`](https://github.com/enzoacoelho/gitactions-serverest) — Pipeline de testes automatizados com GitHub Actions sobre a API ServeRest.
*   [`jenkins-hub-de-leitura`](https://github.com/enzoacoelho/jenkins-hub-de-leitura) — Pipeline Jenkins integrando testes automatizados do projeto Hub de Leitura.
*   [`cy-interception-docker`](https://github.com/enzoacoelho/cy-interception-docker) — Execução de testes Cypress em modo headless dentro de containers Docker, garantindo ambiente reprodutível.
    *   *Tecnologias:* GitHub Actions, Jenkins, Docker, Docker Compose

## Boas práticas adotadas

Os projetos foram estruturados com mapeamento de cenários baseado em riscos para guiar tanto os testes manuais quanto os automatizados. Na automação, apliquei Page Objects, comandos customizados e centralização de requisições para evitar duplicidade de código, gerenciando a massa com fixtures e Faker. Por fim, a execução foi integrada a relatórios Allure e ferramentas de performance para garantir visibilidade sobre os resultados.
