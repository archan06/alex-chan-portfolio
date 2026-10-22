---
name: Alex Chan, Bulletin of Work
description: Alex Chan's work set as his own course catalogue, on warm black bulletin paper.
colors:
  bulletin-black: "#0A0907"
  bulletin-black-raised: "#110E0A"
  plate: "#161210"
  amber: "#F59E0B"
  amber-pale: "#FCD34D"
  amber-dim: "#92611B"
  rose: "#F43F5E"
  cream: "#F5F0E8"
  prose-cream: "#E8DFD0"
  marginalia: "#A89880"
  dim-marginalia: "#8A7C68"
  rule: "rgba(245,158,11,.36)"
  rule-soft: "rgba(245,158,11,.16)"
typography:
  display:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "clamp(76px, 11.6vw, 176px)"
    fontWeight: 360
    lineHeight: 0.9
    letterSpacing: "-.035em"
  headline:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "clamp(34px, 4.6vw, 60px)"
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: "-.015em"
  title:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "clamp(24px, 2.4vw, 32px)"
    fontWeight: 420
    lineHeight: 1.15
    letterSpacing: "-.01em"
  title-project:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "clamp(30px, 3.4vw, 46px)"
    fontWeight: 420
    lineHeight: 1.15
    letterSpacing: "-.01em"
  lede:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "clamp(19px, 1.6vw, 22px)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "'Source Serif 4', 'Iowan Old Style', Georgia, serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "'Courier Prime', 'Courier New', monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
  code:
    fontFamily: "'Courier Prime', 'Courier New', monospace"
    fontSize: "14px"
    fontWeight: 400
  action:
    fontFamily: "'Courier Prime', 'Courier New', monospace"
    fontSize: "15px"
    fontWeight: 700
  live:
    fontFamily: "'Courier Prime', 'Courier New', monospace"
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: ".08em"
rounded:
  none: "0"
spacing:
  gutter: "clamp(20px, 4.4vw, 64px)"
  margin: "clamp(0px, 7vw, 120px)"
  section: "clamp(72px, 10vw, 136px)"
  entry: "34px"
  entry-project: "44px"
  ledger-row: "11px"
  head: "52px"
components:
  button-primary:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.bulletin-black}"
    typography: "{typography.action}"
    rounded: "{rounded.none}"
    padding: "14px 22px"
  button-primary-hover:
    backgroundColor: "{colors.amber-pale}"
    textColor: "{colors.bulletin-black}"
  link-action:
    textColor: "{colors.amber}"
    typography: "{typography.action}"
  live-mark:
    textColor: "{colors.rose}"
    typography: "{typography.live}"
  running-head:
    backgroundColor: "{colors.bulletin-black}"
    textColor: "{colors.marginalia}"
    typography: "{typography.label}"
    height: "{spacing.head}"
    padding: "0 {spacing.gutter}"
  contents-menu:
    backgroundColor: "{colors.bulletin-black-raised}"
    textColor: "{colors.cream}"
    rounded: "{rounded.none}"
    padding: "12px 18px"
  plate:
    backgroundColor: "{colors.plate}"
    rounded: "{rounded.none}"
    padding: "10px"
---

# Design System: Alex Chan, Bulletin of Work

## Overview

**Creative North Star: "The Course Bulletin"**

The site is Alex's own course catalogue. Every project, role, certification and skill is a catalogued entry: a monospaced code (PRJ 301, EXP 2026, CRT), a term, a serif name and a description in Alex's words. Sections are numbered § chapters under a running head, the title page carries a folio ("p. 1"), the headshot is a captioned plate ("Fig. 1"), and stats are set as a ledger. The page reads like printed matter on warm black paper, not like a developer template.

Density is editorial: generous section spacing, one strict left column of codes and terms (170px) against a serif reading column held to 66ch, and one dominant moment per viewport. Hierarchy is carried by type size and weight, hairline amber rules and position, never by cards, shadows or color fills. A single thin amber reading rule runs down the left margin, draws itself as the reader scrolls, and lights each § marker as its section arrives.

The world rejects the generic AI developer portfolio: glow cards, "Hi, I'm" heroes, bento grids, pill chips.

**Key Characteristics:**
- Warm black bulletin paper with cream serif text and muted mono marginalia.
- Amber is reserved for things you can act on and for the drawn rules; rose only says LIVE.
- Every entry is a row in a catalogue: code and term on the left, name and prose on the right.
- Square corners, hairline rules, no shadows, no pills.
- Motion is limited to the title-page reveal, the scroll-drawn margin rule, and weight shifts on hover.

## Colors

A near-monochrome warm ground with one disciplined amber voice and a single rose signal.

### Primary
- **Bulletin Amber** (amber): links, actions, the 2px rule atop the running head and the footer, the scroll-drawn margin rule, the active contents link and the lit § marker. Never on static text.
- **Pale Amber** (amber-pale): hover state for amber actions and the large contact email link. The italic second line of the title-page name also wears it (see Do's and Don'ts).
- **Dim Amber** (amber-dim): the scrollbar thumb only.

### Secondary
- **Signal Rose** (rose): the LIVE mark and its 7px dot on live projects. Nothing else.

### Neutral
- **Bulletin Black** (bulletin-black): the page ground; the running head is this at 94% opacity with a 6px blur.
- **Raised Black** (bulletin-black-raised): the mobile contents menu panel.
- **Plate** (plate): the frame behind the headshot plate.
- **Cream** (cream): names, headings, ledger values, emphasized words in prose.
- **Prose Cream** (prose-cream): running paragraph text, lede, skill and coursework lists.
- **Marginalia** (marginalia): catalogue codes, terms, taglines, organizations, § symbols in headings, section notes, ledger labels, contents links at rest.
- **Dim Marginalia** (dim-marginalia): the faintest layer: folio, footer line, unlit § markers, "Topics"/"Built with" labels. Lightened to clear 4.5:1 on the ground; do not darken it.
- **Rule** (rule, 36% amber): the hairline under each section heading, above ledgers, the "now offered" caption and the contact links.
- **Soft Rule** (rule-soft, 16% amber): row dividers between entries, ledger rows, department cells, the plate border and the unlit margin rule.

### Named Rules
**The Palette Law Rule.** Amber marks what can be clicked or what is being drawn: links, actions, rules. Codes, § symbols, taglines and labels stay in marginalia even when they look important. If amber appears on something that does nothing, it is wrong.

**The One Signal Rule.** Rose means LIVE. It never decorates, never marks hover, never appears without a working demo behind it.

## Typography

**Display Font:** Source Serif 4, variable with optical sizing (with Iowan Old Style, Georgia)
**Body Font:** Source Serif 4 (same)
**Label/Mono Font:** Courier Prime, 400 and 700 (with Courier New)

**Character:** A bookish variable serif for everything a person would read aloud, paired with a typewriter mono for everything a registrar would file: codes, terms, running heads, metadata and actions.

### Hierarchy
- **Display** (360, clamp 76–176px, 0.9, -.035em): the name on the title page only, set in two lines, the second in italic at 340. 72px at phones under 480px.
- **Headline** (400, clamp 34–60px, 1.04, -.015em): section headings, preceded by a 15px mono § numeral in marginalia.
- **Title** (420, clamp 24–32px, 1.15): entry names in Experience; 24px in Skills departments; clamp 28–40px for the education record; 22–23px for certificates and the title-page list.
- **Title, project** (420, clamp 30–46px): project names, each a full-width entry.
- **Lede** (400, clamp 19–22px, 1.55): the title-page introduction, max 34em.
- **Body** (400, 18px, 1.6): prose at 66ch for entries, 36em for About; 17px under 420px.
- **Label** (Courier Prime 400, 13px): running head, section notes, topics, folio, footer, captions.
- **Code** (Courier Prime 400, 14px): catalogue codes and terms, ledger rows, degree line.
- **Action** (Courier Prime 700, 14–15px): button and link text for actions.
- Taglines, organizations and certifying bodies are serif italic in marginalia.

### Named Rules
**The Weight Carries State Rule.** Hover on an entry raises its name's variable weight (420 to 600 on entries, 400 to 640 on the title-page list) over .35s with cubic-bezier(.16,1,.3,1). Color does not change; the type thickens.

**The Two Registers Rule.** Serif for names and prose, mono for codes, metadata and actions. Never set a name in mono or a code in serif.

## Layout

The page frame is a sticky 52px running head (50px under 960px) over a single `main` column padded by the gutter (clamp 20–64px) plus a left margin (clamp 0–120px). The reading rule sits in that margin at 45% of its width; § markers ride on it at each section's top.

Sections open with clamp(72px, 10vw, 136px) of space and a heading row: headline left, an optional mono note right-aligned (max 34ch), closed by a hairline rule. Catalogue entries are a two-column grid, 170px for code and term against the reading column, with clamp(24px, 4vw, 56px) between; projects add a third right column for LIVE and links and get 44px vertical padding instead of 34px. The title page splits 7/12 and 5/12, as do About (7/4) and Education (7/5). Skills is a 2x2 grid of departments with hairline dividers, lists in two text columns. Contact ends with four equal link cells.

At 960px and below: the margin collapses, the rule moves to the gutter, § markers hide, the contents become a disclosure menu, and every grid stacks to one column (contact links go 2x2). Under 480px the title tightens. No horizontal scroll at any width.

## Elevation & Depth

Flat. There are no shadows anywhere. Depth comes from tonal steps (bulletin-black, raised black, plate) and from hairline amber rules at two strengths. The running head separates itself with 94% opacity, a 6px backdrop blur and a soft-rule bottom border.

### Named Rules
**The Paper Rule.** Nothing floats. A layer is distinguished by a slightly warmer black or a hairline, never by a shadow or glow.

## Shapes

Square corners throughout (0 radius): buttons, the plate, the contents menu, rules. The only round forms are the 7–8px status dots (the rose LIVE dot and the cream "open to internships" dot). Lines are 1px hairlines, with 2px solid amber reserved for the top of the running head, the footer and the drawn margin rule. Icons are a three-glyph inline SVG sprite (outbound arrow, next arrow, chevron) drawn at 1.6 stroke with square caps, sized 0.9em in currentColor.

## Components

### Buttons
Typewritten and blunt.
- **Shape:** square (0).
- **Primary:** amber fill, bulletin-black text, Courier Prime 700 at 15px, 14px 22px padding (12px 18px under 480px), with a trailing next-arrow icon. One per surface: "Read the resume".
- **Hover / Focus:** fill shifts to pale amber over .2s; focus is a 2px amber outline at 3px offset (global).
- **Text action:** amber mono 700 with an underline that draws in from the left over .3s on hover/focus and follows line breaks.

### Catalogue Entry (signature)
The core unit of the world. A row with a mono code (e.g. PRJ 301) and term on the left, a serif name, italic tagline or organization, prose and a mono "Topics" / "Built with" line on the right, separated from the next by a soft rule. Projects add a right column with the LIVE mark and amber action links with outbound icons. Hover thickens the name.

### Ledger
Facts set as accounting rows: mono 14px, label in marginalia left, value in cream right, 11px row padding, soft-rule dividers, opened by a full-strength rule. Used for About stats and Education details. Stats are never big-number tiles.

### Live Mark
Rose mono 700 at 12px, .08em tracking, preceded by a 7px rose dot. Only on projects with a working demo.

### Navigation
- **Running head:** sticky, 2px amber top rule, Courier Prime 13px. Left: "ALEX CHAN · BULLETIN OF WORK, 2026–27" in cream with an amber middot. Right: the § contents in marginalia; hover goes cream; the current section goes amber with a 1px amber underline (scroll-spy).
- **Mobile:** an amber "Contents" disclosure with chevron opens a raised-black panel with a full-strength rule border, cream links, 12px 18px padding; selecting a link closes it.

### Margin Rule and § Markers (signature)
A 1px soft-rule line down the left margin with a 2px amber line inside that scales from 0 to full height linked to scroll. Each section's § marker (mono 15px, dim marginalia on a bulletin-black chip) turns amber when that section is current. Hidden at 960px and below except the unlit line.

### Plate
The headshot in a plate-colored frame with a soft-rule border, 10px padding, 4:5 crop, and a mono 12px caption in "Fig. 1 —" form.

## Do's and Don'ts

### Do:
- **Do** give every new entry a mono catalogue code and term in the 170px left column.
- **Do** keep amber to links, actions and drawn rules, and rose to LIVE only.
- **Do** separate rows with soft rules (16% amber) and open groups with full rules (36% amber).
- **Do** show hover by raising variable font weight, not by color or lift.
- **Do** set facts and stats as a ledger of label/value rows.
- **Do** keep motion to the title-page reveal (lines rise 110% to 0 over 1.1s, staggered .12s, ease cubic-bezier(.16,1,.3,1)), the scroll-drawn margin rule and hover weight shifts, and drop all of it under prefers-reduced-motion.
- **Do** keep dim text at dim-marginalia or lighter for contrast.

### Don't:
- **Don't** use rounded corners, pill chips or tag badges; skills and topics are plain text lists separated by middots.
- **Don't** use shadows, glows or gradient fills.
- **Don't** put amber on codes, § symbols, taglines or labels.
- **Don't** use bento grids or card tiles; entries are full-width rows.
- **Don't** add a second italic-amber display moment; the pale-amber "Chan" on the title page is a one-off of the name, not a heading treatment.
- **Don't** color a single word inside a section heading.
