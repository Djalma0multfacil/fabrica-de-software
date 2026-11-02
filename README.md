# Fábrica de Software Starter Pack (Multi-LLM Guide)

## O que é?
O **Fabrica de Software Starter Pack** é um framework agnóstico de LLM desenvolvido para automatizar a tradução de atas de reuniões, PRDs e requisitos de software em uma esteira ágil sincronizada (Trello + GitHub Projects/Issues). Ele integra nativamente a skill **`criacao-cards`** para garantir rigor estético e estrutural nos cartões do Trello.

## Como implementar em outras LLMs (Copilot, Gemini, Claude Code)

### 1. GitHub Copilot (`.github/copilot-instructions.md`)
Copie o conteúdo conceitual e as regras da skill (incluindo as diretrizes de `criacao-cards`) para dentro do arquivo de instruções do Copilot no seu repositório. O Copilot passará a seguir o padrão de criação de issues granulares e cartões padronizados.

### 2. Claude Code (`CLAUDE.md` ou prompt do sistema)
Adicione as diretrizes de governança do Trello x GitHub e padronização de cartões no arquivo `CLAUDE.md` do projeto. O Claude usará essa instrução para governar comandos via terminal e geração de artefatos ágeis.

### 3. Gemini CLI (`.gemini/skills/fabrica-de-software/SKILL.md` e `.gemini/skills/criacao-cards/SKILL.md`)
Estas skills já estão nativamente instaladas neste repositório. Quando acionada, a Fábrica de Software dialoga diretamente com a skill de criação de cards para garantir consistência em todos os municípios.
