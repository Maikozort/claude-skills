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

## Plugins

Los plugins no viven en esta carpeta; se instalan desde su marketplace. Instalados localmente:

```bash
claude plugin install discord@claude-plugins-official
```

Los demás plugins (marketing, data, design, productivity, adobe-for-creativity, postiz, etc.) llegan sincronizados desde la cuenta de claude.ai y no hace falta instalarlos a mano. La carpeta `synced/` se ignora por lo mismo.
