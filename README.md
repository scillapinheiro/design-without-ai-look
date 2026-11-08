# Design without the AI look

A skill for Claude that helps you design and code templates and websites that do not look AI-made. It gives Claude a default list of habits to avoid (status pills, numbered sections, decorative slashes, generic card grids and more), asks it to define an identity for each project before drawing, and ends with a review.

The list is a starting point. You can add your own things to avoid, release default habits you actually like, and swap the suggested alternative for any habit.

**Install only one language folder.** The three folders do the same job. If you install more than one, Claude will load them all at once.

| Language | Folder |
| --- | --- |
| English | `design-without-ai-look` |
| Português | `design-sem-cara-de-ia` |
| Español | `diseno-sin-cara-de-ia` |

## How to install

**Claude (app and website):** download this repository as a zip, then zip the one language folder you want (the folder must contain `SKILL.md` at its top level) and upload it in Settings, in the Skills area. Menu names change over time, so check the current ones.

**Claude Code:** copy the language folder to `~/.claude/skills/`, or to `.claude/skills/` inside a single project.

## How to customize

Add a block like this to your `CLAUDE.md`, your brief, or just tell Claude in the conversation:

```
## Design without the AI look: adjustments
Also avoid: sticky notes, rounded stat cards
Release (no need to remove): status pills
Preferred alternatives: use a plain line instead of a slash between menu items
```

If no adjustments exist, the skill asks once and writes your answer into this block.

## What is inside

- Step 0: your adjustments, which override every default rule.
- Step 1: identity before layout (concept universe, skeleton, palette and type, brand element).
- Default habits to avoid, each with an alternative.
- What to do, rules for code, and a final review with a logo test and a neighbor test.

## Português

Uma skill para o Claude que ajuda a criar templates e sites sem cara de IA. Traz uma lista padrão de vícios a evitar (pílulas de status, seções numeradas, barras decorativas, grades de cards genéricos e outros), pede uma identidade para cada projeto antes de desenhar e termina com uma revisão. Você pode acrescentar proibições suas, liberar vícios padrão de que gosta e trocar a alternativa sugerida. Instale só uma pasta de idioma: `design-sem-cara-de-ia`.

## Español

Una skill para Claude que ayuda a crear plantillas y sitios web sin cara de IA. Incluye una lista por defecto de vicios que evitar (píldoras de estado, secciones numeradas, barras decorativas, cuadrículas de tarjetas genéricas y más), pide una identidad para cada proyecto antes de diseñar y termina con una revisión. Puedes añadir tus propias prohibiciones, liberar vicios por defecto que sí te gustan y cambiar la alternativa sugerida. Instala solo una carpeta de idioma: `diseno-sin-cara-de-ia`.

## License

MIT. See `LICENSE`.
