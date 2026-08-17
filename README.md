# Portfólio de Engenharia de Qualidade

[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)](https://github.com/enzoacoelho)
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)](https://github.com/enzoacoelho)
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)](https://github.com/enzoacoelho)
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)](https://github.com/enzoacoelho)
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)](https://github.com/enzoacoelho)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)](https://github.com/enzoacoelho)
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

- **[`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp)** — Numa aplicação de pagamentos entre usuários, o risco está concentrado em transações e autenticação. Separei a suíte em Page Objects, Components (elementos repetidos entre abas) e Commands (ações genéricas), pra evitar que uma mudança de UI quebrasse vários testes ao mesmo tempo.
- **[`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura)** — Sistema com permissões diferentes por perfil de usuário, então a estratégia priorizou cobrir regras de negócio e autorização, não só status code. CI no GitHub Actions publica relatório Allure a cada execução, pra dar visibilidade contínua sobre o estado da suíte.
- **[`pw-api-shortbeyond`](https://github.com/enzoacoelho/pw-api-shortbeyond)** — Antes de automatizar, explorei a API manualmente com Bruno pra mapear o contrato de cada rota. Além dos testes funcionais, simulei um cenário de pico de tráfego com Artillery (carga estável → pico súbito → queda), pra observar como a API se comporta fora da condição ideal.

> Os READMEs individuais desses três projetos trazem contexto completo, estratégia de testes e evidências.

## Projetos

Projetos desenvolvidos ao longo dos meus estudos, organizados por categoria.

### 1. Testes Manuais e Estratégias
- [`qa-manual-todo-list`](https://github.com/enzoacoelho/qa-manual-todo-list) — Testes funcionais, exploratórios e edge cases numa Todo List, gerenciados no Jira/Zephyr Scale.

### 2. Automação Web
- [`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp) *(destaque acima)*
- [`pw-streaming`](https://github.com/enzoacoelho/pw-streaming) — E2E com Playwright numa plataforma de streaming (login, leads, catálogo), com integração a PostgreSQL.

### 3. Automação Mobile
- [`appium-wdio`](https://github.com/enzoacoelho/appium-wdio) — Automação Android com Appium + WebDriverIO.
- [`appium-robot-yodapp`](https://github.com/enzoacoelho/appium-robot-yodapp) — Automação mobile com Robot Framework.

### 4. Automação de API
- [`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura) *(destaque acima)*
- [`pw-api-shortbeyond`](https://github.com/enzoacoelho/pw-api-shortbeyond) *(destaque acima)*

### 5. Testes de Performance
- [`k6-tests`](https://github.com/enzoacoelho/k6-tests) — Scripts de carga com k6, com análise de latência, taxa de erro e throughput.

### 6. DevOps e Infraestrutura de Testes (CI/CD & Containers)
- [`cy-interception-docker`](https://github.com/enzoacoelho/cy-interception-docker) — Testes Cypress headless em containers Docker, garantindo ambiente reprodutível.

## Boas práticas adotadas

Os projetos foram estruturados com mapeamento de cenários baseado em riscos para guiar tanto os testes manuais quanto os automatizados. Na automação, apliquei Page Objects, comandos customizados e centralização de requisições para evitar duplicidade de código, gerenciando a massa com fixtures e Faker. A execução foi integrada a relatórios Allure e ferramentas de performance para garantir visibilidade sobre os resultados.
