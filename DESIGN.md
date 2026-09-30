---
name: Olivia Koeppen, Instructional Design Portfolio
description: A campus-wayfinding system for a small academic portfolio. One garnet sign per page, then plain directories.
colors:
  garnet: "#8a1c32"
  garnet-deep: "#6a1426"
  garnet-sign-dark: "#7a1a2e"
  rose-dark-accent: "#f59fb1"
  rose-dark-hover: "#fbc4cf"
  sign-secondary: "#f6dce2"
  ground: "#ffffff"
  panel: "#f4f2f5"
  ink: "#17151a"
  ink-secondary: "#57505c"
  rule: "#d9d5dc"
  bar-track: "#e7e3ea"
  ground-dark: "#141216"
  panel-dark: "#1e1b21"
  ink-dark: "#f2eff3"
  ink-secondary-dark: "#b5aebb"
  rule-dark: "#37323b"
typography:
  display:
    fontFamily: "Overpass, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "clamp(2.75rem, 8vw, 5.5rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "Overpass, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "clamp(1.6rem, 3.4vw, 2.1rem)"
    fontWeight: 700
    lineHeight: 1.12
  title:
    fontFamily: "Overpass, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 700
    lineHeight: 1.12
  body:
    fontFamily: "Source Serif 4, Iowan Old Style, Palatino Linotype, Georgia, serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Overpass, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 700
rounded:
  none: "0"
spacing:
  gutter: "clamp(1rem, 4vw, 2.5rem)"
  section: "clamp(3rem, 7vw, 5rem)"
  wrap: "72rem"
components:
  button-primary:
    backgroundColor: "{colors.garnet}"
    textColor: "{colors.ground}"
    rounded: "{rounded.none}"
    padding: "0.8rem 1.25rem 0.7rem"
  button-primary-hover:
    backgroundColor: "{colors.garnet-deep}"
    textColor: "{colors.ground}"
  sign-panel:
    backgroundColor: "{colors.garnet}"
    textColor: "{colors.ground}"
  path-marker:
    backgroundColor: "{colors.garnet}"
    textColor: "{colors.ground}"
    size: "2.75rem"
---

# Design System: Olivia Koeppen, Instructional Design Portfolio

## Overview

**Creative North Star: "Campus Wayfinding"**

Olivia's work is making courses navigable, so the site behaves like a good university signage system. Every page opens with one sign: a full-width garnet panel that says where you are and what this is. Everything below it is quiet and orderly: white ground, near-black ink, hairline rules, and directory rows with a label column and a value. It should read like careful course material or a strong department page, never like a creative portfolio.

The garnet panel is the only bold move on a page. Color is confident rather than muted, with real contrast in both themes. Boise State blue/orange and College of Western Idaho colors are excluded by brand commitment.

**Key Characteristics:**
- One garnet sign panel per page; no other colored fields.
- Directory rows (label column plus value) for facts, contact, and lists.
- Square corners, no shadows, 1px rules and 2px section bars.
- Overpass for everything navigational; Source Serif 4 for reading.

## Colors

One saturated garnet on a neutral, slightly cool ground.

### Primary
- **Garnet** (#8a1c32): the sign panel field, links, path markers, outcome figures, primary button, focus ring (light theme).
- **Garnet Deep** (#6a1426): hover for links and the primary button.
- **Night Garnet** (#7a1a2e): the sign panel in dark theme.
- **Rose** (#f59fb1) / **Rose Light** (#fbc4cf): accent and hover on dark ground, where garnet would fail contrast.

### Neutral
- **Ground** (#ffffff / dark #141216): page background.
- **Panel** (#f4f2f5 / dark #1e1b21): quiet tint for the checklist footer.
- **Ink** (#17151a / dark #f2eff3): text and 2px section bars.
- **Ink Secondary** (#57505c / dark #b5aebb): dates, summaries, figure labels. At least 6.9:1 on its grounds.
- **Rule** (#d9d5dc / dark #37323b): hairlines between rows.
- **Sign Secondary** (#f6dce2 / dark #f2cbd3): role line, subtitle, breadcrumb on the garnet panel.

### Named Rules
**The One Sign Rule.** A page has exactly one garnet field, at the top. Garnet elsewhere appears only as ink: links, small markers, figures, one button.

## Typography

**Display Font:** Overpass (fallback Helvetica Neue, Arial, system-ui)
**Body Font:** Source Serif 4 (fallback Iowan Old Style, Palatino, Georgia)

**Character:** Overpass descends from Highway Gothic, the lettering of road and campus signs; it carries names, headings, labels, nav and figures. Source Serif 4 carries every paragraph, so the reading feels like a well-set course document.

### Hierarchy
- **Display** (800, clamp(2.75rem, 8vw, 5.5rem), 1.0): the name on the home sign. Case study titles use clamp(2.25rem, 5.5vw, 3.75rem).
- **Headline** (700, clamp(1.6rem, 3.4vw, 2.1rem), 1.12): section headings, sitting under a 2px ink bar.
- **Title** (700, 1.2 to 1.6rem): project titles, path roles, checklist groups.
- **Body** (400, 1.125rem, 1.6): paragraphs, max 68ch.
- **Label** (600 to 700, 0.9 to 1rem): directory labels, dates, nav, figure labels. Sentence case, no tracking, no uppercase.
- **Figure** (800, clamp(2rem, 4.5vw, 3.5rem), tabular lining numerals, garnet): outcome numbers.

## Layout

Single 72rem container with a fluid gutter (1rem at phone width). Sections are separated by clamp(3rem, 7vw, 5rem) and open with a 2px ink bar. At 56rem and up, case-study sections use a split: a 15rem heading column and a text column. The case-study sign is two columns from 60rem (text and facts left, a white aside right with the artifact or outcome). Path steps use marker / date / body columns from 56rem. Everything collapses to one column at phone width with no horizontal scroll.

## Elevation & Depth

Flat. No shadows anywhere. Depth comes from the garnet field against white, the white aside set into the garnet, and rules.

## Shapes

Square corners throughout (radius 0). Borders are 1px hairlines between rows, 2px ink for section bars and the artifact document frame. Checkboxes in the checklist are drawn 2px squares.

## Components

- **Top bar:** wordmark left, text nav right; current section underlined 2px garnet. New items (About, Resume) append to the list.
- **Sign panel:** garnet field; name or breadcrumb plus title, role or subtitle, intro, and a directory of facts.
- **Directory row:** `dl` with a label column (7.5 to 9.5rem) and value; stacks under 30rem.
- **Path step:** garnet square marker with the step number; the future step uses an outlined marker.
- **Project row:** title link covers the row; summary; "Read the case study" with an arrow that moves 4px on hover; outcome figure right.
- **Artifact document:** 2px-framed document with a head, grouped checklists (real `ul`), and a tinted foot.
- **Outcome bars:** before/after bars (decorative, values in text) for numeric comparisons.
- **More projects:** wayfinding list at the foot of each case study.
- **Primary button:** garnet block, Overpass 700, arrow icon; hover darkens.

## Do's and Don'ts

- Do keep one garnet sign per page.
- Do show artifacts as real HTML when they are text; offer the original file as a download.
- Do put outcome numbers in Overpass 800 garnet, with the label in plain words beside them.
- Don't add cards, shadows, rounded corners, gradients, or eyebrow labels above headings.
- Don't use muted or washed-out tints, or Boise State / CWI colors.
- Don't add placeholder sections; omit anything without real content.
