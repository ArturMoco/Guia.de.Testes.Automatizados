
# 🧪 Guia Profissional de Testes Automatizados — QA Automation Engineer (HumanIT)

---

## 🎯 Visão Geral / Overview

Olá, sou **Artur Felipe Albuquerque Portela**, candidato à vaga de **QA Automation Engineer na HumanIT**.  
Este guia resume o **meu processo de testes automatizados**, alinhado com as melhores práticas internacionais.

Hi, I'm **Artur Felipe Albuquerque Portela**, candidate for the **QA Automation Engineer position at HumanIT**.  
This guide summarizes **my automated testing process**, aligned with international best practices.

---

## 🎯 Objetivo / Objective

Garantir a qualidade do software através de testes automatizados contínuos e bem documentados, cobrindo cenários críticos, regressões e integrações. O foco está em entregar valor de forma ágil, confiável e escalável.

Ensure software quality through continuous and well-documented automated testing, covering critical scenarios, regressions, and integrations. The focus is on delivering value in an agile, reliable, and scalable manner.

---

## 🗂️ Estrutura Padrão / Project Structure (Cypress)

```
project-root/
├── cypress/               # Testes Cypress / Cypress tests
│   ├── e2e/               # Casos de teste / Test cases
│   ├── fixtures/          # Dados de teste / Test data
│   ├── support/
│   │   ├── commands.js    # Comandos customizados / Custom commands
│   │   └── e2e.js         # Suporte global / Global support
├── evidencias/            # Prints manuais / Manual screenshots
├── screenshots/           # Prints automáticos / Auto screenshots
├── videos/                # Gravações / Video recordings
├── cypress.config.js      # Configuração Cypress / Cypress config
├── jenkinsfile            # Pipeline CI/CD
├── README.md              # Documentação / Documentation
├── package.json           # Dependências / Dependencies
```

---

## 🧰 Ferramentas / Tools I Use

| Categoria / Category             | Ferramentas / Tools                             |
|----------------------------------|-------------------------------------------------|
| Testes E2E / UI Testing          | Cypress, Selenium WebDriver                     |
| Testes de API / API Testing      | Postman (Newman), RestAssured, cy.request()     |
| Relatórios / Reporting           | Allure, ExtentReports                           |
| Integração Contínua / CI/CD      | Jenkins, GitHub Actions, Azure DevOps           |
| Performance Testing              | JMeter, Blazemeter                              |
| Microserviços / Microservices    | Arquitetura desacoplada / Decoupled architecture|
| Comunicação de falhas / Alerts   | Slack, Microsoft Teams, Email                   |
| Containers / Isolation           | Docker, Cypress Dashboard                       |
| Cobertura / Code Coverage        | nyc, JaCoCo, Coverlet                           |

---

## 🔁 Processo de Testes / Test Flow

### 1. Planejamento / Planning
- Reuniões com time de produto / Meetings with product team
- Escrita dos critérios de aceitação (Gherkin) / Writing acceptance criteria
- Priorização de fluxos críticos / Prioritizing critical flows

### 2. Desenvolvimento / Test Development
- `describe()` por funcionalidade / per feature  
- `it()` por cenário / per scenario  
- Scroll dinâmico com `scrollIntoView()`  
- Comandos reutilizáveis com `Cypress.Commands.add()`  
- Dados isolados em `fixtures/`

### 3. Execução / Execution
- Execução local e CI/CD  
- Ambientes separados (.env.qa, .env.dev)  
- Automatização por pull request / trigger on PR

### 4. Evidências e Relatórios / Evidence & Reports
- `cy.screenshot()` automático  
- Vídeos de execução  
- Allure/ExtentReports com logs e prints  
- Notificações automatizadas

---

## ✅ Diferenciais / Key Differentials

- Experiência real com CI/CD pipelines
- Organização, documentação e testes de ponta a ponta
- Excelente comunicação com equipas técnicas e produto
- Capacidade de adaptar testes para microserviços, APIs e interfaces
- Relatórios visuais + evidência automatizada

---

📌 **Artur Felipe Albuquerque Portela**  
🗓️ **Julho 2025 / July 2025**

> Documento elaborado com base na vaga internacional publicada pela **HumanIT** e alinhado ao [Guia de Padronização de Projetos de Teste Automatizados - Artur Portela]
