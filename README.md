# Portfólio de Engenharia de Qualidade

[![CI](https://img.shields.io/badge/CI-GitHub_Actions-blue?logo=githubactions&logoColor=white)](https://github.com/seu-usuario)
[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)](https://github.com/seu-usuario)
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)](https://github.com/seu-usuario)
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)](https://github.com/seu-usuario)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)](https://github.com/seu-usuario)
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)](https://github.com/seu-usuario)
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)](https://github.com/seu-usuario)
[![JMeter](https://img.shields.io/badge/JMeter-Performance-D22128?logo=apachejmeter&logoColor=white)](https://github.com/seu-usuario)
[![JUnit](https://img.shields.io/badge/JUnit-Unit_Testing-25A162?logo=junit5&logoColor=white)](https://github.com/seu-usuario)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://github.com/seu-usuario)



Este repositório reúne meus projetos práticos em Engenharia de Qualidade de Software, organizados para apresentar minha evolução no aprendizado de testes, automação, DevOps e qualidade de forma clara e objetiva.

Aqui estão concentrados trabalhos que envolvem testes manuais, automação web, mobile, testes de API, testes de unidade, performance, containers, integração contínua e uso de IA aplicada à qualidade — sempre baseados em cenários próximos à realidade de aplicações de mercado.

## Objetivo do portfólio

- Demonstrar minha experiência prática em qualidade de software
- Apresentar projetos desenvolvidos ao longo dos meus estudos
- Mostrar a aplicação de boas práticas de testes, automação e organização
- Evidenciar minha capacidade de analisar contexto, definir estratégia e tomar decisões técnicas

Mais do que listar ferramentas, este portfólio busca mostrar como eu penso em qualidade.

## Destaques — comece por aqui

Se você tem pouco tempo, estes três projetos resumem bem minha forma de trabalhar:

- **[`cypress-rwa`](https://github.com/seu-usuario/cypress-rwa)** — Fork do Cypress Real World App migrado de Yarn para NPM, com ambiente configurado para rodar frontend e API localmente de forma integrada. Mostra capacidade de adaptar um projeto real a um novo setup.
- **[`hub-de-leitura-cucumber-cypress`](https://github.com/seu-usuario/hub-de-leitura-cucumber-cypress)** — Testes E2E em BDD com Cucumber/Gherkin, ligando cenários de negócio à automação técnica.
- **[`k6-tests`](https://github.com/seu-usuario/k6-tests)** — Scripts de performance com análise de métricas, indo além do "rodar o teste" até interpretar risco e gargalo.

*(Ajuste esses três para os projetos dos quais você mais se orgulha ou que tiveram maior complexidade de decisão.)*

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

Projeto voltado à base analítica de QA, cobrindo cenários baseados em risco e documentação ágil.

**Foco:** priorização de casos de teste por risco, escrita de cenários claros e reportes de bug estruturados o suficiente para agilizar o retrabalho do time de desenvolvimento.

**Repositório:** [`qa-manual-agile-travel`](https://github.com/seu-usuario/qa-manual-agile-travel)

### 2. Testes de Unidade

Exemplos de testes aplicados a funções e regras de negócio isoladas, com foco em confiabilidade e manutenção do código.

**Tecnologias utilizadas:**
- JavaScript
- Jest
- Java
- JUnit

**Repositórios:**
- [`jest-logic-challenges`](https://github.com/seu-usuario/jest-logic-challenges) — Exercícios de lógica em JS, focados em cobertura de casos-limite.
- [`teste-de-unidade-jest`](https://github.com/seu-usuario/teste-de-unidade-jest) — Testes unitários aplicados a regras isoladas de negócio.
- [`junit-sistema-bancario`](https://github.com/seu-usuario/junit-sistema-bancario) — Sistema bancário em Java com JUnit, validando regras críticas como saldo e transações.

### 3. Automação Web (UI)

Testes end-to-end (E2E) simulando a jornada real do usuário em aplicações web.

**Tecnologias utilizadas:**
- Cypress
- Playwright
- JavaScript / TypeScript
- NPM

**Repositórios:**
- [`cypress-rwa`](https://github.com/seu-usuario/cypress-rwa) — Fork do Cypress Real World App. Projeto adaptado e migrado de Yarn para NPM, configurado para execução local integrada com o frontend rodando na porta 3000 e a API Backend na porta 3001.
- [`pw-streaming`](https://github.com/seu-usuario/pw-streaming) — Automação E2E de uma plataforma de streaming utilizando Playwright, cobrindo fluxos de navegação e reprodução de conteúdo.

### 4. Automação de API

Validações de regras de negócio, testes funcionais e de contrato diretamente na camada de serviços.

**Tecnologias utilizadas:**
- Playwright
- Cypress
- Testes de API REST

**Repositórios:**
- [`hub-de-leitura-api-teste`](https://github.com/seu-usuario/hub-de-leitura-api-teste) — Validação de regras de negócio e cenários positivos/negativos da API do Hub de Leitura.
- [`shortBeyond-playwright`](https://github.com/seu-usuario/shortBeyond-playwright) — Testes de contrato e cenários funcionais via Playwright.

### 5. UI Avançado

Cenários complexos de interface que exigem controle sobre o comportamento assíncrono e regras de negócio guiadas por comportamento.

**Tecnologias utilizadas:**
- Cypress
- Cucumber / Gherkin
- Mocking HTTP (`cy.intercept`)

**Repositórios:**
- [`hub-de-leitura-cucumber-cypress`](https://github.com/seu-usuario/hub-de-leitura-cucumber-cypress) — BDD ligando cenários de negócio escritos em Gherkin à automação técnica.
- [`cy-interception`](https://github.com/seu-usuario/cy-interception) — Mock de dados e controle de rede para simular cenários difíceis de reproduzir (erros de API, latência, respostas inesperadas).

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
