---
name: fabrica-de-software
description: "Fabrica de Software Starter Pack: Transforma atas de reuniões, PRDs ou requisitos de negócios em uma esteira ágil sincronizada entre Trello (Épicos/Sub-épicos de negócios e homologação) e GitHub Projects/Issues (detalhamento técnico granular e sub-issues, estruturado com o padrão de 3 views)."
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

## Padrão de Configuração do GitHub Projects (3 Views Obrigatórias)
Todo projeto criado no GitHub Projects através desta skill deve ser estruturado com **três visualizações (Views)** padronizadas:
1. **View 1 (Table / Tabela):** Visão analítica geral contendo todas as issues, repositórios, assignees, milestones e progresso de sub-issues.
2. **View 2 (Board / Kanban):** Quadro Kanban agrupado por **Status** contendo estritamente as 5 colunas do fluxo de entrega:
   - `Em esteira` (Issues abertas sem branch)
   - `Desenvolvimento` (Issues abertas com branch/PR ativo)
   - `Em homologação` (Issues com branch mergeada no ambiente de homologação)
   - `Homologação concluída` (Issues finalizadas e testadas em homologação)
   - `Em produção` (Issues com branch fechada e mergeada na `develop` em ambos os repositórios)
3. **View 3 (Roadmap):** Cronograma temporal configurado com os campos customizados `Start Date` e `Target Date`, sincronizados com o progresso e o status das issues no Kanban.

## Fluxo de Execução
1. Processar a ata de reunião ou PRD.
2. Extrair o Épico principal e os Sub-épicos.
3. Gerar as Issues granulares no GitHub e criar o GitHub Project configurando as **3 Views obrigatórias** (Table, Kanban Board com 5 colunas e Roadmap).
4. Organizar as issues como sub-issues (checklists) nos respectivos sub-épicos.
5. Sincronizar o Trello e criar cartões macro aplicando estritamente as diretrizes da skill **`criacao-cards`** (modelo visual de Franco da Rocha, títulos em LETRAS MAIÚSCULAS, etiquetas e cores específicas por município, e consistência estrutural).
