
# 🧪 Guia Profissional de Testes Automatizados — QA Engineer (CodeWin)

## 🎯 Visão Geral / Overview

Olá, sou **Artur Felipe Albuquerque Portela**, profissional de QA com foco em **testes automatizados de qualidade em projetos de transformação digital**.  
Este guia resume o **meu processo de testes**, alinhado com as melhores práticas do mercado e adaptável a sistemas ERP, CRM, webapps e APIs.

Hi, I'm **Artur Felipe Albuquerque Portela**, a QA professional focused on **automated quality testing in digital transformation projects**.  
This guide summarizes **my testing process**, aligned with best practices and adaptable to ERP, CRM, web apps, and APIs.

## 🎯 Objetivo / Objective

Contribuir para o sucesso dos projetos da CodeWin com **testes eficientes, confiáveis e bem documentados**, garantindo cobertura de fluxos críticos e regressões em ambientes complexos e integrados.

Contribute to CodeWin's project success with **efficient, reliable, and well-documented testing**, ensuring coverage of critical flows and regressions in complex and integrated environments.

## 🗂️ Estrutura Padrão / Project Structure (Cypress)

```
project-root/
├── cypress/               # Testes automatizados / Automated tests
│   ├── e2e/               # Fluxos principais / Main flows
│   ├── fixtures/          # Dados de teste / Test data
│   ├── support/
│   │   ├── commands.js    # Comandos reutilizáveis / Reusable commands
│   │   └── e2e.js         # Configurações globais / Global setup
├── evidencias/            # Prints manuais / Manual screenshots
├── screenshots/           # Capturas automáticas / Auto screenshots
├── videos/                # Execuções gravadas / Execution videos
├── cypress.config.js      # Configuração geral / General config
├── jenkinsfile            # Integração contínua / CI pipeline
├── README.md              # Documentação técnica / Technical doc
├── package.json           # Dependências / Dependencies
```

## 🧰 Ferramentas / Tools I Use

| Categoria / Category             | Ferramentas / Tools                             |
|----------------------------------|-------------------------------------------------|
| Testes E2E / UI Testing          | Cypress, Selenium WebDriver                     |
| Testes de API / API Testing      | Postman, Newman, cy.request(), RestAssured      |
| Integração Contínua / CI/CD      | Jenkins, GitHub Actions, Azure DevOps           |
| Relatórios / Reporting           | Allure, ExtentReports                           |
| Contêineres / Containers         | Docker, Cypress Dashboard                       |
| Cobertura de Código / Coverage   | nyc, Coverlet, JaCoCo                           |
| Comunicação / Team Integration   | Slack, MS Teams, Email                          |
| Testes de Performance            | JMeter, Blazemeter                              |

## 🔁 Processo de Testes / Testing Flow

### 1. Planeamento / Planning
- Reuniões com stakeholders  
- Análise dos requisitos (funcionais e técnicos)  
- Escrita de critérios de aceitação em **Gherkin**  
- Identificação de fluxos de risco e regressão

### 2. Desenvolvimento de Testes / Test Development
- Separação de funcionalidades com `describe()`  
- Cenários detalhados com `it()`  
- Ações repetidas em comandos (`Cypress.Commands.add()`)  
- Dados dinâmicos isolados em `fixtures/`  
- Scroll dinâmico com `scrollIntoView()` para estabilidade

### 3. Execução / Execution
- Execução local e via pipeline (CI/CD)  
- Testes por ambiente (QA, DEV, STG) com `.env` isolado  
- Triggers por Pull Request ou schedule

### 4. Evidências e Relatórios / Evidence & Reporting
- Screenshots automáticos por falha ou passo-chave  
- Gravações em vídeo completas  
- Geração automática de relatórios com logs e evidências  
- Notificação da equipa com o resultado dos testes

## ✅ Diferenciais / Key Differentials

- Experiência real com pipelines CI/CD integrados ao processo de desenvolvimento  
- Organização e documentação clara de testes E2E e de APIs  
- Adaptação fácil a projetos de ERP, CRM, microserviços e arquitetura desacoplada  
- Rigor na geração de evidência automatizada e rastreável  
- Comunicação fluida com equipas técnicas e de negócio  
- Testes escritos com foco em valor de negócio e cobertura crítica

📌 **Artur Felipe Albuquerque Portela**  
🗓️ **Julho 2025 / July 2025**

> Documento adaptado com foco na vaga de QA para projetos de desenvolvimento e transformação digital na **CodeWin**
