# Fábrica de Software Starter Pack (Multi-LLM Guide)

## O que é?
O **Fabrica de Software Starter Pack** é um framework agnóstico de LLM desenvolvido para automatizar a tradução de atas de reuniões, PRDs e requisitos de software em uma esteira ágil sincronizada (Trello + GitHub Projects/Issues).

## Como implementar em outras LLMs (Copilot, Gemini, Claude Code)

### 1. GitHub Copilot (`.github/copilot-instructions.md`)
Copie o conteúdo conceitual e as regras da skill para dentro do arquivo de instruções do Copilot no seu repositório. O Copilot passará a seguir o padrão de criação de issues granulares e organização de épicos.

### 2. Claude Code (`CLAUDE.md` ou prompt do sistema)
Adicione as diretrizes de governança do Trello x GitHub no arquivo `CLAUDE.md` do projeto. O Claude usará essa instrução para governar comandos via terminal e geração de documentação de arquitetura.

### 3. Gemini CLI (`.gemini/skills/fabrica-de-software/SKILL.md`)
Esta skill já está nativamente instalada neste repositório. Quando acionada, ela carrega automaticamente as diretrizes de engenharia, classificação técnica e sincronização ágil.
