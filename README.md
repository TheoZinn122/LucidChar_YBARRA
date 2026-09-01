[![DevOps Production Pipeline](https://github.com/TheoZinn122/LucidChar_YBARRA/actions/workflows/devops-pipeline.yml/badge.svg)](https://github.com/TheoZinn122/LucidChar_YBARRA/actions/workflows/devops-pipeline.yml)
# Fluxo DevOps End-to-End

Este repositório contém a implementação prática da esteira de CI/CD baseada no fluxo de arquitetura projetado no Lucidchart.

## Diagrama de Arquitetura (Lucidchart)

<img width="2360" height="1320" alt="Blank diagram" src="https://github.com/user-attachments/assets/9df9caa9-eaef-4335-8c29-cf1de28e5ab9" />

### Fases da Pipeline Automatizada
* **1. Testes & SAST:** Execução de testes unitários e análise de segurança estática.
* **2. Build & Push:** Construção e publicação de contêiner imutável com a tag do commit.
* **3. Homologação (Staging):** Deploy em ambiente de validação e QA.
* **4. Produção:** Rollout seguro da aplicação com zero downtime.
