# Skills de Claude Code (Mogameson)

Skills personales que usa Claude Code en cualquier proyecto: publicación (`publicar`, `copy`, `ficha-*`, `portada`, `analizar-video`), `watch`, Remotion, ponytail y otras.

## Instalar en otro computador (Windows)

```bash
git clone https://github.com/Maikozort/claude-skills.git "$HOME/.claude/skills"
```

Si la carpeta `~/.claude/skills` ya existe, muévela o bórrala antes de clonar.

## Mantenerlas al día

- Después de cambiar una skill: `git add -A && git commit -m "..." && git push`
- En el otro computador: `git pull`

## Skills de Anthropic (sincronizadas desde claude.ai)

`algorithmic-art`, `brand-guidelines`, `canvas-design`, `doc-coauthoring`, `docs`, `docx`, `google-workspace`, `import-memory`, `internal-comms`, `mcp-builder`, `morning`, `pdf`, `pptx`, `skill-creator`, `slack-gif-creator`, `theme-factory`, `web-artifacts-builder`, `xlsx`.

## Plugins (`plugins/`)

Copia de los plugins instalados: `adobe-for-creativity`, `cowork-plugin-management`, `data`, `design`, `discord`, `marketing`, `postiz`, `productivity`. Claude Code no los carga desde esta carpeta (no tiene `SKILL.md` en la raíz); sirven de respaldo. Para usarlos, instálalos desde el marketplace o con `/plugin` apuntando a la carpeta. El plugin `discord` necesita `bun install` (se excluyó `node_modules`).
