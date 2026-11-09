---
name: "design-without-ai-look"
description: "Use when designing or coding templates and websites to avoid the generic AI look: own identity, customizable default habits to avoid, realistic copy and a final review."
---

# Design without the AI look

Use this skill whenever you design a layout, build a design in a tool (Figma, Canva and so on) or turn a design into code. The goal: every project has its own identity, does not look like it came out of a generator, and does not look like another project by the same person.

## Step 0: the person's adjustments (they override every rule below)

The list of habits in this skill is a starting point. The person can change it in three ways:

1. **Add** their own things to avoid (a decoration that showed up too often, a shape, a writing habit).
2. **Release** default habits they do not want removed (for example, "pills are fine" or "slashes are fine").
3. **Swap the alternative** suggested for a habit, if they prefer another one.

Look for these adjustments in CLAUDE.md, README, the brief or the conversation, in a block like this:

```
## Design without the AI look: adjustments
Also avoid: ...
Release (no need to remove): ...
Preferred alternatives: ...
```

If there are no adjustments, ask once, in one sentence: "Do you want to add something you never want to see, or release any of the default habits?". Write the answer into the block above and follow it for the whole project. Restate the rules in force at the start of the work.

## Step 1: identity before layout

Answer in writing before designing:
1. What is the concept's universe (objects, materials, places, era, sounds)?
2. What is the skeleton (order and shape of the sections)? Is it different from projects already made?
3. What is the palette (3 to 5 colors, each with a job) and the typography (two families at most)? Does neither repeat another project's?
4. What is the brand element? Something made only for this concept, that would make no sense in another.

If the skeleton, palette or typography look like another project's, change them before going on.

If no other projects are in view, ask for one reference, or skip the comparison and say that you skipped it.

If the person already has brand colors, fonts or a logo, those are the identity. Use them and build the rest (composition, shapes, tone) around them. Question 3 then becomes: which of the brand's colors and fonts do I use, and for what job?

## Habits that give AI work away (each one can be released in Step 0)

**Status pills and tags.** Rounded labels such as "NEW", "ON SALE", "LIVE", category tags used as decoration. Alternative: plain text placed well, or an element from the concept's universe (stamp, seal, ticket, button). A label is only worth it when it carries information the visitor needs at that point. Why: generators add a status label to every block to look busy and current, and a label that carries no news is just noise.

**Numbering.** Page, section or card numbers ("01", "02", "Page 2 of 5"), decorative counters and statistics with no source. Real data that is needed (dates, times, durations, prices) is fine. Why: numbers suggest a process or a ranking the content does not have, and statistics with no source look invented.

**Tiny uppercase label** above a big headline, repeated in every section. Alternative: a headline that stands on its own. Why: it is a stock gesture for adding hierarchy, and repeated in every section it becomes a template stamp.

**Glows and shine**, diffuse colored shadows, generic purple and blue gradients. Alternative: flat color with a clear job. Why: they are the default of image models and gradient presets, so they say "generated" at first glance.

**A grid of three identical cards** with icon, title and sentence. Alternative: a layout built for the content. Why: it fills a row without deciding what matters, so the grid shapes the content instead of the other way around.

**Generic line icons** instead of art made for the concept. Why: they come from the same few icon sets everyone uses, so they say nothing about this concept.

**Vague marketing phrases** ("Elevate your sound", "Crafted with passion") and **lorem ipsum**. Write specific copy, with plausible names, places and dates. Why: a phrase that could describe any product describes none, and placeholder text hides whether the layout works with real words.

**Illustrating where the person will put their own photo.** Illustration is brand art; photo spaces stay empty and easy to swap. Why: the person will replace it anyway, and it hides the fact that a photo is still missing.

**The same composition in every section** (centered title, button below, image behind). Alternative: one visual idea per section. Why: repeating one layout makes the page read as a single idea stretched out.

## The author's own pet peeves (on by default, release freely)

These are matters of taste more than signs of AI. They are on by default because the author of this skill dislikes them. Release any of them in Step 0.

**Slashes as separators.** A single slash ("/") or double slash ("//") between words, in menus, labels, dates or credits. Alternative: a space, a middle dot, a line, or an element from the concept. Why: it is a decorative stand-in for a separator, common in generated menus, dates and credits.

**Dashes in the text.** Use a comma, a period or a colon. Why: long dashes are one of the most recognizable habits of generated text.

**Italic serif** as an automatic "elegant touch". Why: it is an automatic way of looking elegant that turns up in a lot of generated work.

## Do

- Each section has its own visual idea tied to the concept, not just a block of text on a background.
- One dominant element per screen, with room around it.
- A type scale with real contrast (headline much bigger than body).
- Copy in a real person's voice: specific, short, no cliché.
- WCAG AA contrast at minimum. If there is an approved design or brief and it fails, tell the person and propose a fix instead of changing it alone.
- If there is already an approved layout, respect it: if the code or the review needs a change to it, ask first.

## Code

- Semantic HTML, CSS variables at the top for colors, fonts and sizes.
- When turning an existing design into code, keep fidelity to it: same sections, order, texts, colors and fonts.
- Animation with a purpose tied to the concept, not a generic entrance effect on everything.
- Illustrations and brand elements in SVG, not raster images.

## Final review (before showing)

1. Check the person's adjustments and the list of habits above, item by item. Look especially for forgotten pills, numbers, slashes and dashes in menus, footers, cards and supporting text.
2. Logo test: if I removed the logo, would anyone know which project this is? If not, identity is missing.
3. Neighbor test: put it next to another project by the same person. If swapping the name and the color would be enough to confuse the two, redo the skeleton. If no other work is in view, ask for one reference or skip this test and say that you skipped it.
4. Report what you found and what you changed.
