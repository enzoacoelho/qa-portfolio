# Portfólio de Engenharia de Qualidade

[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)](https://github.com/enzoacoelho)
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)](https://github.com/enzoacoelho)
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)](https://github.com/enzoacoelho)
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)](https://github.com/enzoacoelho)
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)](https://github.com/enzoacoelho)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)](https://github.com/enzoacoelho)
[![Zephyr Scale](https://img.shields.io/badge/Zephyr_Scale-Test_Management-F26522?logo=jira&logoColor=white)](https://github.com/enzoacoelho)
[![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/enzoacoelho)

💡 Ex-desenvolvedor migrando pra Qualidade de Software.

## Sobre mim

4 anos como desenvolvedor, hoje em transição pra QA — trago bagagem técnica pra além da execução de testes.

Uso essa bagagem para ler código com profundidade e dialogar de igual para igual com times de dev. Aqui estão meus projetos práticos de testes manuais, automação e integração contínua.

## Objetivo do portfólio

- Demonstrar minha experiência prática em qualidade de software
- Apresentar projetos desenvolvidos ao longo dos meus estudos
- Mostrar a aplicação de boas práticas de testes, automação e organização
- Evidenciar minha capacidade de analisar contexto, definir estratégia e tomar decisões técnicas

## Stack

| Categoria | Ferramentas |
|---|---|
| Web (E2E) | Cypress, Playwright |
| API | Cypress, Playwright |
| Mobile | Appium, WebDriverIO, Robot Framework |
| Performance | k6, Artillery |
| CI/CD & Containers | GitHub Actions, Docker |
| Gestão de testes manuais | Jira Cloud, Zephyr Scale |

## Destaques

Projetos que melhor representam como eu penso estratégia de teste, não só execução:

- **[`Teste Manual - (Tool Shop)`](https://github.com/enzoacoelho/qa-manual-toolshop)** — Testes manuais e exploratórios em um e-commerce de ferramentas. Foquei em análise de risco e cenários de borda no checkout, mapeando matriz de rastreabilidade, ciclos e relatórios de bugs com evidências visuais. (Jira e Zephyr)
- **[`Testes de API Automatizados - Hub de Leitura (Cypress)`](https://github.com/enzoacoelho/cy-api-hub-de-leitura)** — Automação de API (Cypress) em um sistema de biblioteca. Foco total em regras de negócio e validação de permissões por perfil (autorização), com relatórios Allure integrados via CI/CD no GitHub Actions.
- **[`Testes Web Automatizados E2E - Streaming (Playwright)`](https://github.com/enzoacoelho/pw-streaming.git)** — Automação de testes E2E com Playwright e JavaScript em aplicação web de streaming, com testes funcionais dos fluxos de login, leads e catálogo e cenários de teste automatizados.

> Os READMEs individuais desses três projetos trazem contexto completo, estratégia de testes e evidências.

## Projetos

Projetos desenvolvidos ao longo dos meus estudos, organizados por categoria.

### 1. Testes Manuais e Estratégias
- [`qa-manual-toolshop`](https://github.com/enzoacoelho/qa-manual-toolshop) — Suíte de testes manuais, funcionais, exploratórios e cenários de borda (edge cases) para a aplicação web "Practice Software Testing - Tool Shop", estruturada com matriz de rastreabilidade, ciclos de execução e relatórios de defeitos (bugs).
- [`qa-manual-agileway-travel`](https://github.com/enzoacoelho/qa-manual-agileway-travel) — Suíte de testes manuais, funcionais, exploratórios e cenários de borda (edge cases) para o ecossistema de reservas de viagens da AgileWay, gerenciada com planejamento de ciclos e reporte estruturado de falhas.

### 2. Automação Web
- [`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp) — App de pagamentos entre usuários *(destaque acima)*
- [`pw-streaming`](https://github.com/enzoacoelho/pw-streaming) — E2E com Playwright numa plataforma de streaming (login, leads, catálogo), com integração a PostgreSQL.

### 3. Automação Mobile
- [`appium-wdio`](https://github.com/enzoacoelho/appium-wdio) — Automação Android com Appium + WebDriverIO no app oficial de exemplo do WebdriverIO (puzzles/quiz).
- [`appium-robot-yodapp`](https://github.com/enzoacoelho/appium-robot-yodapp) — Automação mobile com Robot Framework num app de gerenciamento de tarefas.

### 4. Automação de API
- [`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura) — Sistema de biblioteca com permissões por perfil *(destaque acima)*
- [`pw-api-shortbeyond`](https://github.com/enzoacoelho/pw-api-shortbeyond) — Encurtador de links, com testes de carga *(destaque acima)*

### 5. Testes Unitários (Jest)
- [`jest-viacep`](https://github.com/enzoacoelho/jest-viacep) — Função que busca endereço pelo CEP na API pública do ViaCEP, com 16 testes unitários e 100% de cobertura. O `fetch` é mockado com `jest.fn()`, então os testes rodam sem internet e simulam cenários difíceis de reproduzir de verdade (API fora do ar, falha de rede, resposta quebrada). Cobre também casos de borda de entrada (CEP com hífen, ponto, espaços, número, vazio, letras e dígitos a mais) e usa `test.each` para evitar repetição.
- [`jest-api`](https://github.com/enzoacoelho/jest-api) — API REST de usuários com Express, testada com Jest e Supertest: 26 testes e cerca de 98% de cobertura. Valida regras de negócio (maioridade, email, usuário ativo e email único), status codes (201, 400, 404, 409, 204), JSON quebrado e o ciclo completo cadastro, listagem, busca e remoção. Cada teste começa com os dados limpos, e `app.js` fica separado de `server.js` para testar sem subir servidor.

### 6. Testes de Performance
- [`k6-tests`](https://github.com/enzoacoelho/k6-tests) — Scripts de carga com k6, com análise de latência, taxa de erro e throughput.

### 7. DevOps e Infraestrutura de Testes (CI/CD & Containers)
- [`cy-interception-docker`](https://github.com/enzoacoelho/cy-interception-docker) — Testes Cypress headless em containers Docker, garantindo ambiente reprodutível.

## Boas práticas adotadas

Os projetos foram estruturados com mapeamento de cenários baseado em riscos para guiar tanto os testes manuais quanto os automatizados. Na automação, apliquei Page Objects, comandos customizados e centralização de requisições para evitar duplicidade de código, gerenciando a massa com fixtures e Faker. A execução foi integrada a relatórios Allure e ferramentas de performance para garantir visibilidade sobre os resultados.
