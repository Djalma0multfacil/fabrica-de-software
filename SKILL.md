---
name: fabrica-de-software
description: "Fabrica de Software Starter Pack: Transforma atas de reuniões, PRDs ou requisitos de negócios em uma esteira ágil sincronizada entre Trello (Épicos/Sub-épicos de negócios e homologação) e GitHub Projects/Issues (detalhamento técnico granular e sub-issues)."
---

# Fábrica de Software Starter Pack

## Visão Geral
Esta skill orienta a IA a atuar como um Arquiteto de Software e Tech Lead, processando documentos de requisitos, atas de reuniões e gerando automaticamente a estrutura completa de gestão ágil de forma padronizada.

## Regras e Convenções
1. **Separação de Responsabilidades:**
   - **Trello:** Nível macro (Épicos e Sub-épicos). Visibilidade executiva e critérios de homologação funcional/negócios. Títulos em **LETRAS MAIÚSCULAS**, etiquetas padronizadas e checklists de negócio.
   - **GitHub Projects & Issues:** Nível técnico granular. Sub-issues detalhadas, checklists de resolução técnica, testes, e rastreabilidade de Pull Requests.
2. **Classificação Técnica vs. Negócios:**
   - *Restritamente Técnicos (Backend/APIs):* Validados por suíte de testes e code review, sem homologação visual na ponta.
   - *Homologáveis (Ponta/Front-end/Negócios):* Telas, validações de formulário e fluxos de usuário visíveis para clientes.

## Fluxo de Execução
1. Processar a ata de reunião ou PRD.
2. Extrair o Épico principal e os Sub-épicos.
3. Gerar as Issues granulares no GitHub.
4. Organizar as issues como sub-issues (checklists) nos respectivos sub-épicos.
5. Sincronizar o Trello apenas com os épicos macro e orientações para a equipe de projetos.
