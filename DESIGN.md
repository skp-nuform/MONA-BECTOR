---
name: Mona Bector
description: A career laid out as a working program roadmap on a transformation office's planning wall.
colors:
  paper: "#f7f8f6"
  grid: "#e6e8e4"
  grid-strong: "#d5d8d3"
  rule: "#c9cdc7"
  sheet: "#ffffff"
  ink: "#1a1d23"
  ink-2: "#3d434d"
  ink-3: "#5b626d"
  public: "#0f766e"
  public-soft: "#d5ebe8"
  enterprise: "#a15c07"
  enterprise-soft: "#f3e4cf"
  cred: "#1d4ed8"
  cred-soft: "#dbe4fb"
  night-tab: "#2a2e36"
  night-text: "#c3c8c0"
  cred-night: "#8fa8f5"
typography:
  display:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "clamp(44px, 5.4vw, 78px)"
    fontWeight: 600
    lineHeight: 0.96
    letterSpacing: "-0.04em"
    fontFeature: "tnum"
  display-light:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "clamp(44px, 5.4vw, 78px)"
    fontWeight: 300
    lineHeight: 0.96
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "clamp(34px, 4vw, 56px)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.025em"
  lead:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
    fontFeature: "tnum"
  label:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1.3
    fontFeature: "tnum"
  meta:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.45
rounded:
  hair: "2px"
  sm: "4px"
  md: "6px"
  lg: "8px"
  xl: "10px"
  pill: "999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  grid: "24px"
  lg: "32px"
  xl: "48px"
  2xl: "64px"
  section-mobile: "80px"
  section: "120px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sheet}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0 20px"
    height: "48px"
  button-primary-sm:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sheet}"
    rounded: "{rounded.md}"
    padding: "0 14px"
    height: "40px"
  button-primary-inverse:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "0 20px"
    height: "48px"
  chip-lane:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.pill}"
    padding: "0 12px"
    height: "34px"
  chip-lane-active:
    backgroundColor: "#f1f2ef"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
  tag-org:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: "0 11px"
    height: "32px"
  roadmap-bar-public:
    backgroundColor: "{colors.public}"
    textColor: "{colors.sheet}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "0 9px"
    height: "30px"
  roadmap-bar-enterprise:
    backgroundColor: "{colors.enterprise}"
    textColor: "{colors.sheet}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "0 9px"
    height: "30px"
  phase-tab:
    backgroundColor: "{colors.night-tab}"
    textColor: "{colors.night-text}"
    rounded: "{rounded.sm}"
    padding: "0 16px"
    height: "56px"
  phase-tab-selected:
    backgroundColor: "{colors.cred}"
    textColor: "{colors.sheet}"
    rounded: "{rounded.sm}"
---

# Design System: Mona Bector

## Overview

**Creative North Star: "The Program Roadmap Wall"**

The page is a transformation office's planning wall: a cool white sheet ruled with a faint plotter grid, graphite ink, and three workstream inks laid down as solid schedule bars. A career is not narrated; it is scheduled. Roles are bars on lanes, certifications are milestone diamonds, the present is a dashed "today" line, and the visitor reads it the way a sponsor reads a Gantt chart. Everything else on the page (work packages, phases, places, credentials) borrows the same instruments: WBS codes, hairline rules, lane-coloured swatches, diamonds.

Density is that of a working document, not a brochure. Sections are separated by generous air (120px) but inside each one the information is tight, tabular and ruled. The only liveliness comes from interaction: a year cursor scrubbing the chart, bars drawing in once in schedule order, lane filters, an accordion of places. Nothing moves for decoration.

The build rejects the executive-portfolio template: no headshot-headline-stat-row hero, no vertical timeline, no testimonial carousel, no employer logo wall.

**Key Characteristics:**
- Faint 24px plotter grid on cool paper as the ground of every light section; the same grid in white at 5% on the graphite method band.
- Three lane inks with fixed meanings: teal is public sector, ochre is enterprise and consulting, cobalt is credentials and AI.
- One typeface, Public Sans, with tabular figures everywhere so years and codes align.
- Hairline rules and a 1.5px graphite frame instead of cards and shadows.
- Photographs are duotone under a lane ink until chosen, then shown in full colour.

## Colors

A near-neutral graphite-on-paper sheet carrying three saturated workstream inks, each with one pale companion.

### Primary
- **Graphite Ink** (ink): text, the primary button, the roadmap frame, the today line, the year cursor and its label, selected-bar ring, the monogram block, and the full-bleed method and closing bands.

### Secondary (the lane inks)
- **Program Teal** (public): public-sector bars and swatches; ground colour of public-sector place panels. Pale companion **Teal Wash** (public-soft) backs the portrait stand-in.
- **Contract Ochre** (enterprise): enterprise and consulting bars and swatches; ground of the Leidos place panel. Pale companion **Ochre Wash** (enterprise-soft).
- **Credential Cobalt** (cred): milestone diamonds, certificate markers, language scale fill, the selected phase tab, focus outline, text selection, and the ground of the method photo. On graphite it lightens to **Night Cobalt** (cred-night) for outlined diamonds. Pale companion **Cobalt Wash** (cred-soft).

### Neutral
- **Plotter Paper** (paper): page ground and the sticky header (at 94% opacity).
- **Grid Line** (grid): the 24px plotter grid and the roadmap's yearly columns.
- **Grid Line Strong** (grid-strong): lane separators inside the roadmap; unlit language-scale cells.
- **Hairline Rule** (rule): row dividers, chip and tag borders, header underline, detail-panel top rule.
- **Sheet White** (sheet): the roadmap panel, lane-name column, chips, tags; text on ink and lane bars.
- **Ink Two** (ink-2): secondary prose, leads, nav links.
- **Ink Three** (ink-3): metadata, axis years, WBS codes, captions, hints, footer.
- **Night Tab** (night-tab) and **Night Text** (night-text): unselected phase tabs and secondary text on the graphite band.

### Named Rules
**The Lane Meaning Rule.** Teal, ochre and cobalt each mean one workstream and nothing else. A swatch, bar, diamond or photo ground in a lane ink always names that lane; never use them as general accents.

**The Graphite Action Rule.** The one action, "Contact me on LinkedIn", is always solid graphite on light ground and solid white on graphite ground. Lane inks never carry a call to action.

## Typography

**Display Font:** Public Sans (with system-ui, sans-serif), weights 300 to 700, loaded from Google Fonts.
**Body Font:** Public Sans.
**Label/Mono Font:** Public Sans with `font-variant-numeric: tabular-nums` set on the root.

**Character:** The US federal design system's own face, used plainly. It reads as public-sector paperwork done well: neutral, legible, slightly civic, with figures that line up in a schedule.

### Hierarchy
- **Display** (600 over 300, clamp(44px, 5.4vw, 78px), 0.96, -0.04em): the hero name only. The name sets in 600; the role line beneath it drops to 300 at the same size.
- **Headline** (600, clamp(34px, 4vw, 56px), 1.02, -0.025em): section heads. The closing head runs larger, clamp(40px, 5.4vw, 80px) at line-height 1, capped at 14ch.
- **Title** (600, 22 to 30px, 1.2 to 1.25): work-package names (24px), detail-panel title (22px), phase-panel statement (30px, max 24ch).
- **Lead** (400, 19 to 20px, 1.5): hero lead (max 46ch) and section intros (max 52ch) in Ink Two.
- **Body** (400, 17px, 1.55): prose; panel descriptions capped at 68ch.
- **Label** (600, 12 to 13px): bar labels, milestone names, axis years, today and cursor tags.
- **Meta** (400 to 500, 13 to 15px): chips, tags, captions, credential issuers, dates, WBS codes.

### Named Rules
**The Tabular Figures Rule.** Every number on the page sits in tabular figures (set once on `:root`). Years, WBS codes and dates must align in columns.

**The One Face Rule.** Public Sans carries everything; contrast comes from weight (300 against 600) and size, never from a second family.

## Layout

A centred column of `min(100% - 2 × gutter, 1280px)` with a fluid gutter of clamp(20px, 4vw, 80px). Sections carry 120px of vertical padding (80px under 860px). Section heads are a two-column 5fr/7fr grid aligned to the baseline, headline left and intro right; the hero uses 7fr/5fr. Content blocks inside sections use 7fr/5fr or 4fr/8fr splits with 48 to 64px gaps.

The 24px plotter grid is a page-level background on `body`, not a layout grid: content does not snap to it, it simply sits on it like a sheet on a planning wall. The roadmap draws its own grid of thirteen yearly columns.

Spacing rhythm observed in the build: 4, 8, 12, 16, 20, 24, 28, 32, 48, 64, 80, 120px.

**Responsive behaviour.**
- **At 860px and below:** the header nav hides (brand and button stay); every two-column grid (hero, section heads, method, credentials, about) collapses to one column; work-package rows stack; the detail panel stacks and loses its hint; phase tabs become a 2 × 2 grid; the places accordion turns vertical (closed panels 120px tall, the open one 280px, captions horizontal).
- **At 560px and below:** the brand name is visually hidden leaving the MB monogram; the roadmap keeps a 760px minimum width inside a horizontal scroller that opens scrolled to the recent years; the lane-name column dissolves into sticky white labels that sit above each lane; the axis label column is removed; a "Swipe the chart sideways" line appears in the roadmap bar.
- The roadmap scroller exists at every width (920px minimum with its 168px sticky lane column) so the chart never compresses below legibility.

## Elevation & Depth

Flat. There are no drop shadows anywhere. Depth is made with line weight and ground: a 1.5px graphite frame around the white roadmap panel lifts it off the gridded paper, the sticky header separates with one hairline, and whole sections invert to graphite. The only `box-shadow` in the system is a two-ring focus/selection halo on roadmap bars (2px white, then 2px lane ink or graphite), which reads as a plotter outline, not a lift.

### Shadow Vocabulary
- **Bar halo** (`box-shadow: 0 0 0 2px #fff, 0 0 0 4px var(--c)`): hovered or cursor-crossed bar, in its own lane ink.
- **Bar selected** (`box-shadow: 0 0 0 2px #fff, 0 0 0 4px var(--ink)`): the bar currently shown in the detail panel.

### Named Rules
**The Line Not Lift Rule.** Separate surfaces with a rule, a frame or a ground change. If something needs to stand out, give it a heavier line, never a shadow.

## Shapes

Small, near-square corners that keep the drafting-table feel: 2px on the roadmap frame, diamonds and swatches; 3px on the today and cursor tags; 4px on bars, tags and phase tabs; 6px on buttons; 8px on photo panels; 10px on the portrait slot. Lane chips are the only pill shape.

The diamond (a 45° rotated square with a 2px corner) is the recurring glyph: solid for a major certification, outlined for a minor one. It appears as roadmap milestones, credential list markers, phase-panel list bullets and the credentials chip swatch. Small 9 to 10px squares in lane ink are the swatch for a workstream. Dashed 2px graphite lines mean "now or next": the today line on the chart and the open "Your transformation program" bar in the closing band.

## Components

### Buttons
Solid, compact and unadorned: one kind of button, one action.
- **Shape:** gently squared (6px radius).
- **Primary:** graphite ground, white 600 16px text, 48px tall, 20px side padding, with a 16px drawn arrow after the label.
- **Small:** 40px tall, 14px padding, 15px text, used in the sticky header without the arrow.
- **Inverse:** on the graphite closing band, white ground with graphite text; hover shifts to a cool off-white (#e9ecf3).
- **Hover / Focus:** ground deepens to black; the arrow slides 3px right; press nudges down 1px. Focus is the global 2px cobalt outline at 3px offset.

### Chips (lane filters)
- **Style:** 34px pill, white ground, hairline border, 500 14px Ink Two text, led by a 10px swatch in the lane ink (the credentials swatch is a diamond).
- **State:** pressed chip takes a graphite border, graphite text and a faint grey ground (#f1f2ef). Filtering fades non-matching bars and diamonds to 18% opacity rather than removing them, so the schedule keeps its shape.

### Organisation tags
- **Style:** 32px, 4px radius, white ground, hairline border, 500 14px graphite text, lane-ink square swatch.
- **Behaviour:** a tag is a jump link to its bar on the roadmap; hover darkens the border and lifts 1px.

### Navigation
- Sticky 64px header on paper at 94% opacity with a hairline under it. Left: a 34px graphite monogram tile (MB, 700 13px) and the name. Centre: five anchors in Ink Two at 15px, 28px apart, whose hover draws a 1px graphite underline in from the left. Right: the small primary button.

### Program Roadmap (signature component)
The page's world in one instrument.
- **Frame:** white panel, 1.5px graphite border, 2px radius. A toolbar row holds the title and lane chips; a detail panel sits under the chart.
- **Lanes:** a 168px sticky white name column (600 14px, with a 13px Ink Three count beneath) beside plots ruled into thirteen yearly columns with Grid Line. Lanes are separated by Grid Line Strong. The axis row prints years in 13px Ink Three.
- **Bars:** 30px tall, 4px radius, solid lane ink, white 600 13px label on one line with ellipsis, stacked in 36px rows from 12px. A bar too short for its label prints the label in lane ink just outside to its left.
- **Milestone diamonds:** 14px solid cobalt for major certifications, 10px white with a 2px cobalt outline for minor ones, labelled beneath in 600 12px cobalt. Hover or selection scales the diamond 1.35×.
- **Today line:** 2px dashed graphite across all lanes (solid in the axis row), tagged in the credentials lane with a graphite label: "Today, November 2026 · open to new roles".
- **Year cursor:** on hover-capable pointers, a 1px graphite rule follows the pointer across all lanes with a graphite year tag at its top; every bar and diamond it crosses takes its halo.
- **Detail panel:** a 200px / 1fr / auto grid: lane swatch and years on the left, title, organisation and description in the middle, a short hint on the right. It always shows one item and opens on the most recent role.
- **Keyboard:** every bar and diamond is a button; Left and Right arrows walk the schedule in time order.

### Work-package rows
- A ruled table under a 2px graphite top rule, rows divided by hairlines, in three columns (4fr / 5fr / 4fr): WBS code and package name, what it does, organisation tags.
- **WBS codes** (1.1 to 1.5) sit before the name in 500 15px Ink Three tabular figures.
- Hover sweeps a 3.5% graphite wash in from the left across the row.

### Phase tabs
- On the graphite method band: four equal 56px tabs, 4px gap, 4px radius, Night Tab ground with Night Text 600 16px labels.
- The selected tab fills with cobalt sweeping in from the left; text turns white. Arrow keys move between tabs (roving tabindex).
- The panel beside it gives a 30px statement, a list bulleted with outlined Night Cobalt diamonds, and a "Done at" line in muted grey.

### Places accordion
- A 520px-tall row of five panels, 6px apart, 8px radius. One panel is open at four times the width of the others.
- **Duotone treatment:** closed panels show the photograph in greyscale with raised contrast, multiplied over the panel's lane ink (teal for public sector, ochre for enterprise, cobalt for education); the caption runs vertically. The open panel drops the blend and shows the photograph in full colour with a dark gradient caption (organisation 600 20px, place and years 14px).
- Mouse hover, keyboard focus or a click opens a panel; clicking an open panel jumps to its bar on the roadmap.
- The same greyscale-into-ink treatment carries the method photo (luminosity over cobalt) and the closing band (luminosity over graphite at 34%).

### Credentials list and language scale
- Certifications are a ruled list under a 2px graphite rule, each led by a solid or outlined cobalt diamond, with the year right-aligned in Ink Three.
- Languages show a five-cell scale of 10px bars, filled cobalt to the level held, unfilled in Grid Line Strong.

### Motion
- One easing for everything: `cubic-bezier(.16, 1, .3, 1)`.
- On load, bars wipe in from left to right (clip-path, 0.9s, staggered 70ms in schedule order from 0.25s) and diamonds rise in (0.5s, staggered 60ms from 0.9s). The load sequence runs once and is cleared after 2.6s.
- State changes run 0.2 to 0.3s; the places accordion and phase-tab fill run 0.45 to 0.6s.
- **Reduced motion:** the load sequence is never armed, all transitions and animations are disabled, smooth scrolling is turned off and every bar and diamond renders in place, fully visible.

## Do's and Don'ts

### Do:
- **Do** set every light section on the paper ground with the 24px grid (`--grid` lines at 1px).
- **Do** keep the lane inks bound to their workstreams: teal public sector, ochre enterprise, cobalt credentials and AI.
- **Do** mark certifications with the diamond: solid for major, outlined for minor.
- **Do** separate with hairlines (`--rule`) and a 2px graphite rule at the head of any ruled list or table.
- **Do** keep numbers in tabular figures and Public Sans only.
- **Do** make every chart element a real button with a visible cobalt focus outline and arrow-key navigation.
- **Do** treat photographs as greyscale under a lane ink until they are chosen.
- **Do** make every animation optional: under reduced motion the page is static and complete.

### Don't:
- **Don't** add drop shadows or elevated cards; use a frame, a rule or a ground change.
- **Don't** use a lane ink as a general accent or for the call to action.
- **Don't** introduce a second typeface or a monospace for figures.
- **Don't** add a headshot-and-stat-row hero, a vertical timeline, testimonials or logo walls.
- **Don't** soften corners beyond 10px or use pills for anything except lane chips.
