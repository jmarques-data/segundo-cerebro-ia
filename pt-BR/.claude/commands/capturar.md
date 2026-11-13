---
description: Registra uma captura rápida no 00-inbox/ com data e tags
argument-hint: <o que você quer capturar>
---

Registre o seguinte em uma nova nota em `00-inbox/`:

$ARGUMENTS

Regras:
- Nome do arquivo: `AAAA-MM-DD-titulo-curto.md` (data de hoje, título em kebab-case).
- Frontmatter: `data` (hoje), `tags` (2 a 4 tags sugeridas pelo conteúdo) e `status: inbox`.
- Corpo: o texto capturado, fiel ao que eu disse, com um título curto.
- Siga o CLAUDE.md (pt-BR, sem dados sensíveis).
- Ao final, mostre o caminho do arquivo criado e sugira em qual aba ele deve ser organizado depois.
