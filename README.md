# Claude â†’ Codex: migre ou fique agnÃ³stico

Curso prÃ¡tico INEMA.CLUB (formato v2, com camada de aprendizagem) sobre migrar um setup Claude Code pro Codex CLI ou, melhor, deixar o trabalho independente de modelo: contexto, regras, skills, decisÃµes e handoffs em Markdown portÃ¡til, com Claude, Codex e modelo local como executores.

**Curso no ar:** https://inematds.github.io/curso-claude-codex/

| Idioma | URL |
|---|---|
| PortuguÃªs (original) | https://inematds.github.io/curso-claude-codex/ |
| English | https://inematds.github.io/curso-claude-codex/en/ |
| EspaÃ±ol | https://inematds.github.io/curso-claude-codex/es/ |

As versÃµes EN e ES sÃ£o espelhos completos (`en/`, `es/`, com assets prÃ³prios), geradas por `tools/traduz.py` a partir do PT com verificaÃ§Ã£o de esqueleto de tags. O progresso do aluno Ã© separado por idioma (`inema-course` = `claude-codex-en` / `claude-codex-es`). Toda pÃ¡gina tem o seletor PT / EN / ES no nav.

## Estrutura

| Trilha | Cor | ConteÃºdo |
|---|---|---|
| 1 Â· Fundamentos | emerald | por que separar o cÃ©rebro do modelo, vocabulÃ¡rio, trÃªs nÃ­veis, anatomia do workspace, donos da informaÃ§Ã£o, audit antes de implement |
| 2 Â· MÃ£o na massa | blue | os scripts do kit `agente-claude-codex`: doctor/audit, CLAUDE.md â†’ AGENTS.md, nÃºcleo portÃ¡til, polyskill, readback, handoff/prime |
| 3 Â· Projetos | purple | migrar o primeiro projeto real, MCP e hooks, memÃ³ria curada, terceiro executor (dsh-sandbox), workspace de cliente, a mentalidade |

18 mÃ³dulos, 108 tÃ³picos, ~10h. CurrÃ­culo completo em `CURRICULO.md`.

## Fontes

- Kit e scripts: https://github.com/inematds/agente-claude-codex
- DiagnÃ³stico real da mÃ¡quina (2026-09-14) que serve de caso nos projetos.
- Newsletter "Como migrar do Claude para o Codex â€” ou ficar independente de modelo" e a prompt library "Model-agnostic workspaces" (07 SEP 2026), lidas e reescritas como material didÃ¡tico.

## Traduzir de novo (depois de editar o PT)

```bash
tools/traduz.py --lang en --all --force     # reescreve en/ a partir do PT (claude -p; --engine codex tambÃ©m funciona)
tools/traduz.py --lang es --all --force
tools/traduz.py --lang en --switcher-pt     # reinjeta o seletor de idioma nas pÃ¡ginas PT
```

## Rodar local

Abra `index.html` no navegador. Tudo Ã© self-contained (HTML + Tailwind CDN + `assets/learn.js`); funciona em `file://`. Progresso, notas e dÃºvidas ficam no `localStorage` do navegador e podem ser exportados em .json pelo painel "Jornada".

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/273-claude-codex-migre-ou-fique-agnostico/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe