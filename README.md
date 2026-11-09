<h1 align="center">Design without the AI look</h1>

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.pt-BR.md">Português</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <a href="#computer-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-how-it-works">How it works</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sparkles-what-it-avoids">What it avoids</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#eyes-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=6D4FD8&labelColor=grey">
  <img alt="Type" src="https://img.shields.io/static/v1?label=type&message=SKILL.md&color=137A67&labelColor=grey">
  <img alt="Languages" src="https://img.shields.io/static/v1?label=languages&message=EN%20%C2%B7%20PT%20%C2%B7%20ES&color=lightgrey&labelColor=grey">
  <img alt="Version" src="https://img.shields.io/static/v1?label=version&message=1.0.0&color=lightgrey&labelColor=grey">
</p>

## :computer: Project

**Design without the AI look** is a skill that helps an AI design and code templates, websites and other graphic material (posters, slides, social posts, banners, covers) that does not look AI-made. It was made with Claude and works as a Claude skill; see "Other AI tools" below for the rest.

It started from a real problem: a lot of people want to make templates with AI, and the results all share the same tics. Status pills on everything, numbered sections, decorative slashes, three identical cards in a row, a glow behind the headline. Each one is small, but together they give the work away.

The skill gives the AI a default list of those habits to avoid, asks it to define an identity for each project before drawing anything, and closes with a review.

## :bulb: How it works

- **Your adjustments come first.** The default list is a starting point. You can add your own things to avoid, release default habits you actually like, and swap the suggested alternative for any habit.
- **Identity before layout.** Before drawing, the AI answers in writing: what is the concept's universe, what is the skeleton, which palette and type, and what is the brand element that would make no sense in another project.
- **A list of habits, each with an alternative.** Not just "do not do this", but what to do instead.
- **Any graphic material.** Posters, slides, social posts, banners, covers and site templates. A table in the skill says how each website rule reads in the other formats.
- **A final review.** A logo test (without the logo, would anyone know whose project this is?) and a neighbor test (next to another of your projects, are they easy to confuse?).

## :sparkles: What it avoids

These are the defaults. Every one can be released.

| Habit | Instead |
|---|---|
| Status pills and decorative tags | Plain text placed well, or an element from the concept's universe |
| Page, section and card numbering | Real data only: dates, times, durations, prices |
| Slashes as separators | A space, a middle dot, a line |
| Dashes in the text | A comma, a period or a colon |
| Tiny uppercase label above a big headline | A headline that stands on its own |
| Glows, shine, generic purple and blue gradients | Flat color with a clear job |
| Three identical cards with icon, title and sentence | A layout built for the content |
| Vague marketing phrases and lorem ipsum | Specific copy with plausible names, places and dates |
| The same composition in every section | One visual idea per section |

Slashes, dashes and italic serif are the author's own pet peeves: they are on by default and easy to release. The full list, with the reasons, is in the skill file.

## :eyes: How to use

The repository has three folders with the same skill in three languages.

| Language | Folder |
|---|---|
| English | `design-without-ai-look` |
| Português | `design-sem-cara-de-ia` |
| Español | `diseno-sin-cara-de-ia` |

**Install only one.** If you install more than one, Claude loads them all at once.

### Claude (app and website)

1. Download the zip for your language from the Releases page: `design-without-ai-look-v1.0.0.zip` (English), `design-sem-cara-de-ia-v1.0.0.zip` (Português) or `diseno-sin-cara-de-ia-v1.0.0.zip` (Español). Or download this repository (**Code, Download ZIP**), unzip it and zip the one language folder you want. The folder must have `SKILL.md` at its top level.
2. In Settings, open the Skills area and upload the zip. Menu names change over time, so check the current ones.

### Claude Code

Copy the language folder to `~/.claude/skills/`, or to `.claude/skills/` inside a single project.

### Other AI tools

The skill was made with Claude and has been tested only with Claude. The `SKILL.md` format is an open standard (agentskills.io), and other tools say they read it: check your tool's documentation for the folder it expects. If your tool has no skills folder, paste the content of `SKILL.md`, below its header block, into the project's instruction file, such as `AGENTS.md`.

### Customize it

Add a block like this to your `CLAUDE.md`, to your brief, or just tell Claude in the conversation:

    ## Design without the AI look: adjustments
    Also avoid: sticky notes, rounded stat cards
    Release (no need to remove): status pills
    Preferred alternatives: a plain line instead of a slash between menu items

If there are no adjustments, the skill asks once and writes your answer into this block.

## :memo: License

Released under the MIT license. You can use, copy, adapt and share it, as long as you keep the copyright notice. See [LICENSE](LICENSE).
