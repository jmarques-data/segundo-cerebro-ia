# 🧠 Segundo Cérebro com IA (modelo para Claude Code)

Um "segundo cérebro" em pastas e arquivos Markdown, feito para usar com o **Claude Code**.
Você tira tudo da cabeça, e a IA captura, organiza, revisa e sugere as próximas ações.

> Capturar → Organizar → Agir

## Estrutura

| Aba | Para quê |
|---|---|
| `00-inbox/` | Captura rápida, sem organização |
| `01-projetos-ativos/` | Um arquivo por projeto (status, próximos passos, prazo) |
| `02-skills/` | Skills e processos reutilizáveis |
| `03-agents/` | Agentes e automações |
| `04-vida-pessoal/` | Hobbies, metas, hábitos |
| `05-vida/` | Estudos, fé, relacionamentos (renomeie à vontade) |
| `06-carreira/` | Trabalho, LinkedIn e vagas (uma nota por vaga) |
| `07-editor-videos/` | Roteiros e vídeos |
| `99-arquivo/` | O que foi concluído (nada é apagado) |

## Como usar

1. Baixe ou clone este repositório e abra a pasta no **Claude Code** (terminal, VS Code ou app desktop).
2. O Claude lê o `CLAUDE.md` e passa a seguir as regras do sistema.
3. Use os comandos:
   - `/capturar <texto>`: salva uma nota no `00-inbox/` com data e tags.
   - `/revisar-semana`: lê o que mudou em 7 dias e propõe 3 próximas ações.
   - `/vagas-status`: resume as vagas por status.
4. Peça para o Claude organizar o inbox, criar projetos a partir do modelo ou preencher sua agenda (com o conector do Google Agenda).

## Regras do sistema (`CLAUDE.md`)

- Tudo em português brasileiro.
- Toda nota tem frontmatter com `data`, `tags` e `status`.
- O Claude mostra a alteração e espera sua confirmação antes de editar um arquivo.
- Nunca apaga: o que foi concluído vai para `99-arquivo/`.
- Não registra senhas, dados bancários, documentos ou dados de saúde.

## Dicas

- **Revisão automática:** no app do Claude, agende uma tarefa semanal (por exemplo, domingo às 20h) rodando `/revisar-semana`.
- **Primeiro passo:** peça "me faça perguntas para preencher meu segundo cérebro" e responda no seu ritmo.

## Licença

MIT. Use, adapte e compartilhe.
