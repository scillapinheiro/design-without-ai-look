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

## Default habits to avoid (each one can be released in Step 0)

**Status pills and tags.** Rounded labels such as "NEW", "ON SALE", "LIVE", category tags used as decoration. Alternative: plain text placed well, or an element from the concept's universe (stamp, seal, ticket, button). A label is only worth it when it carries information the visitor needs at that point.

**Numbering.** Page, section or card numbers ("01", "02", "Page 2 of 5"), decorative counters and statistics with no source. Real data that is needed (dates, times, durations, prices) is fine.

**Slashes as separators.** A single slash ("/") or double slash ("//") between words, in menus, labels, dates or credits. Alternative: a space, a middle dot, a line, or an element from the concept.

**Dashes in the text.** Use a comma, a period or a colon.

**Tiny uppercase label** above a big headline, repeated in every section.

**Italic serif** as an automatic "elegant touch".

**Glows and shine**, diffuse colored shadows, generic purple and blue gradients.

**A grid of three identical cards** with icon, title and sentence.

**Generic line icons** instead of art made for the concept.

**Vague marketing phrases** ("Elevate your sound", "Crafted with passion") and **lorem ipsum**. Write specific copy, with plausible names, places and dates.

**Illustrating where the person will put their own photo.** Illustration is brand art; photo spaces stay empty and easy to swap.

**The same composition in every section** (centered title, button below, image behind).

## Do

- Each section has its own visual idea tied to the concept, not just a block of text on a background.
- One dominant element per screen, with room around it.
- A type scale with real contrast (headline much bigger than body).
- Copy in a real person's voice: specific, short, no cliché.
- WCAG AA contrast at minimum. If the design fails, tell the person instead of fixing it alone.
- Respect what is already approved: if the code or the review needs a change to an approved layout, ask first.

## Code

- Semantic HTML, CSS variables at the top for colors, fonts and sizes.
- Fidelity to the design: same sections, order, texts, colors and fonts.
- Animation with a purpose tied to the concept, not a generic entrance effect on everything.
- Illustrations and brand elements in SVG, not raster images.

## Final review (before showing)

1. Check the person's adjustments and the list of habits above, item by item. Look especially for forgotten pills, numbers, slashes and dashes in menus, footers, cards and supporting text.
2. Logo test: if I removed the logo, would anyone know which project this is? If not, identity is missing.
3. Neighbor test: put it next to another project by the same person. If swapping the name and the color would be enough to confuse the two, redo the skeleton.
4. Report what you found and what you changed.
