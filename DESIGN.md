---
name: My Nguyen
description: A calm sky briefing. Pale paper, lake ink, and a serif name.
colors:
  paper-sky: "#f4f9fc"
  cloud-white: "#ffffff"
  lake-ink: "#16324a"
  shore-mist: "#5a7388"
  daylight-blue: "#2e7eae"
  soft-cloud: "#e6f4fb"
  mid-sky: "#5aaad4"
  logo-sky: "#7ec8e8"
  deep-lake: "#12344c"
  entry-water: "#1f6f9c"
  entry-deep: "#15577d"
  rain: "#215777"
  hairline: "rgba(92, 168, 214, 0.22)"
typography:
  display:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(3.2rem, 9vw, 7rem)"
    fontWeight: 700
    lineHeight: 0.92
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "clamp(1.8rem, 3vw, 2.5rem)"
    fontWeight: 700
    lineHeight: 1.65
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Fraunces, Georgia, serif"
    fontWeight: 700
    lineHeight: 1.65
    letterSpacing: "-0.03em"
  body:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "0.82rem"
    fontWeight: 800
    letterSpacing: "0.08em"
rounded:
  pill: "999px"
  card: "18px"
  menu: "14px"
  tab: "12px"
  mark: "10px"
spacing:
  section: "5rem"
  section-compact: "3.4rem"
  gutter: "2rem"
  stack: "1.4rem"
  group: "1.2rem"
  inline: "0.8rem"
  chip: "0.45rem"
components:
  button-primary:
    backgroundColor: "{colors.lake-ink}"
    textColor: "{colors.paper-sky}"
    rounded: "{rounded.pill}"
    padding: "0.78rem 1.15rem"
  button-primary-hover:
    backgroundColor: "{colors.daylight-blue}"
    textColor: "{colors.paper-sky}"
    rounded: "{rounded.pill}"
    padding: "0.78rem 1.15rem"
  button-ghost:
    backgroundColor: "{colors.cloud-white}"
    textColor: "{colors.lake-ink}"
    rounded: "{rounded.pill}"
    padding: "0.78rem 1.15rem"
  button-ghost-hover:
    backgroundColor: "{colors.cloud-white}"
    textColor: "{colors.daylight-blue}"
    rounded: "{rounded.pill}"
    padding: "0.78rem 1.15rem"
  button-start:
    backgroundColor: "{colors.entry-water}"
    textColor: "{colors.cloud-white}"
    rounded: "{rounded.pill}"
    padding: "0.95rem 1.8rem"
  button-start-hover:
    backgroundColor: "{colors.entry-deep}"
    textColor: "{colors.cloud-white}"
    rounded: "{rounded.pill}"
    padding: "0.95rem 1.8rem"
  chip:
    backgroundColor: "{colors.cloud-white}"
    textColor: "{colors.lake-ink}"
    rounded: "{rounded.pill}"
    padding: "0.32rem 0.75rem"
  panel:
    backgroundColor: "rgba(255, 255, 255, 0.72)"
    textColor: "{colors.lake-ink}"
    rounded: "{rounded.card}"
    padding: "1.15rem 1.2rem"
  work-card:
    backgroundColor: "{colors.cloud-white}"
    textColor: "{colors.lake-ink}"
    rounded: "{rounded.card}"
    padding: "1.2rem 1.3rem"
  nav-mark:
    backgroundColor: "{colors.logo-sky}"
    textColor: "{colors.deep-lake}"
    rounded: "{rounded.mark}"
    size: "42px"
  exp-tab-active:
    backgroundColor: "{colors.cloud-white}"
    textColor: "{colors.lake-ink}"
    rounded: "{rounded.tab}"
    padding: "0.75rem 0.7rem"
---

# Design System: My Nguyen

## Overview

**Creative North Star: "The Sky Briefing"**

The Sky Briefing is a pale page that reads as a sheet of findings. A faint sky grid sits behind the type. Fraunces carries the name and the section titles. Plus Jakarta Sans carries the evidence. Decoration stays small: the grid, a hairline, and the clouds at the door.

The page is calm, airy, and precise. Soft sky first, then the facts. Lake Ink does the reading. Daylight Blue marks the few things that should be touched: the second half of the name, a link, a project number, an icon. The START screen is weather you pass through. Behind it, the page is a document.

Depth is a cool lift, not a gray drop. The shared shadow is a wide, faint lake-blue cast. It sits under the mobile menu, and the same cast may sit under cards. Panels stay white and hairlined so the sheet stays easy to read.

**Key Characteristics:**

- Pale sky ground, lake-ink text, one daylight accent
- Serif for the name and titles, sans for the evidence
- A document first: label column, prose, hairline panels
- Pills only on actions and skill tags
- Cool blue lift, and never a dark dashboard

## Colors

One daylight accent on a paper-sky field. The paler blues are weather, not a second signal.

### Primary

- **Daylight Blue** (`#2e7eae`): The accent. It colors the second word of the name, project dates and links, contact icons, and the primary button on hover. It is a mark, not a fill for large areas.

### Secondary

The sky family. Atmosphere, the mark, and hover borders. It does not fill a briefing-page button at rest.

- **Soft Cloud** (`#e6f4fb`): The wash behind contact icons.
- **Mid Sky** (`#5aaad4`): The hover border on ghost buttons and project rows.
- **Logo Sky** (`#7ec8e8`): The fill of the MN mark only.

### Tertiary

The START screen only. These colors do not come back onto the briefing page.

- **Deep Lake** (`#12344c`): The start title, and the letters on the MN mark.
- **Entry Water** (`#1f6f9c`): The START button at rest.
- **Deep Entry** (`#15577d`): The START button on hover and focus, and the links along the bottom of the door.
- **Rain** (`#215777`): The subtitle and the hint under START.

### Neutral

- **Paper Sky** (`#f4f9fc`): The page ground. The sticky header is the same color at 86% opacity.
- **Cloud White** (`#ffffff`): Cards, chips, ghost buttons, the active experience tab, and the mobile menu. Education panels use it at 72% opacity.
- **Lake Ink** (`#16324a`): Reading text, the primary button at rest, and button strokes.
- **Shore Mist** (`#5a7388`): Secondary prose, nav links at rest, metadata, and section labels.
- **Sky Hairline** (`rgba(92, 168, 214, 0.22)`): The 1px edge on panels, cards, the header, and the footer.

### Named Rules

**The Daylight Rule.** Daylight Blue marks a meaning: the emphasized name, a link, a project number, an icon. The paler sky colors are atmosphere. They do not fill a briefing-page button at rest.

**The No Dashboard Rule.** The system stays on Paper Sky. No black canvas, no neon chart colors, no dense instrument panels.

## Typography

**Display Font:** Fraunces (with Georgia, then serif)
**Body Font:** Plus Jakarta Sans (with sans-serif)
**Label/Mono Font:** Plus Jakarta Sans. There is no mono face.

**Character:** The serif is the name and the headings, tracked tight. The sans is the sheet: labels, buttons, and evidence. The pairing stays quiet. Headlines are not uppercase. Uppercase is reserved for the small kickers and section labels.

### Hierarchy

- **Display** (700, `clamp(3.2rem, 9vw, 7rem)`, line-height 0.92, tracking -0.03em): The hero name only. The second word is Daylight Blue and is not italic.
- **Headline** (700, `clamp(1.8rem, 3vw, 2.5rem)`, line-height 1.65, tracking -0.03em): Section titles. The contact line uses the same face at `clamp(2.2rem, 5vw, 3.6rem)`. The START title is Fraunces at `clamp(3rem, 8vw, 5.4rem)`, line-height 1, in Deep Lake.
- **Title** (700, tracking -0.03em, line-height 1.65): Panel headings, role titles, and project names, in Fraunces. No separate size is authored; they sit at the browser heading size. Skill-group labels are the exception: Plus Jakarta Sans at 0.95rem.
- **Body** (400, line-height 1.65): Evidence and biography, in Plus Jakarta Sans. The hero lead is 1.15rem in Shore Mist, held to 40rem, with emphasized words returned to Lake Ink at weight 700. About copy is Shore Mist, held to 62ch.
- **Label** (800, 0.82rem, tracking 0.08em, uppercase): The section labels in the left column, in Shore Mist. The hero kicker is the same idea at 0.85rem, weight 700, tracking 0.16em.

### Named Rules

**The Two Voices Rule.** Fraunces speaks the name and the section titles. Plus Jakarta Sans speaks the evidence. Body copy does not go in the serif, and the hero name does not go in the sans.

## Layout

The page is one sheet. Content sits in a column of 1120px, inset 1rem from each side of the viewport. Sections stack with 5rem of vertical padding, and 3.4rem below 860px.

Each section opens with a 180px label column and a fluid text column, separated by 2rem. Experience widens that side column to 280px. Project rows keep 120px for the date, then the write-up, then the link. Below 860px the label column, the education pair, the experience split, and the project rows all become one column. The link in a project row moves under the text.

The header is 72px tall, sticky, and blurs the sky behind it by 16px. The hero fills the viewport that remains under that bar. Repeated gaps are 2rem between label and copy, 1.4rem before a group of cards or chips, 1.2rem between skill groups and inside the education pair, 0.8rem between buttons, and 0.45rem between chips.

A fixed 72px grid of `rgba(90, 170, 212, 0.08)` lines covers the viewport and does not capture clicks.

### Named Rules

**The One Sheet Rule.** Content sits in a 1120px column. A 180px label column introduces each section, widening to 280px for experience. Below 860px the sheet becomes a single column.

## Elevation & Depth

The page is a flat sheet with a cool lift available when something needs to rise. White panels sit on Paper Sky and are separated by the sky hairline. The header uses blur and a hairline, not a shadow. The active experience tab uses a 1px hairline ring, not a lift.

### Shadow Vocabulary

- **Lake lift** (`box-shadow: 0 18px 40px rgba(46, 126, 174, 0.1)`): The shared shadow. It sits under the mobile menu. The same cast may sit under cards.
- **Entry cast** (`box-shadow: 0 10px 24px rgba(31, 111, 156, 0.28)`): The START button only.
- **Cloud cast** (`filter: drop-shadow(0 8px 12px rgba(46, 126, 174, 0.12))`): The clouds on the START screen.
- **Hairline ring** (`box-shadow: 0 0 0 1px rgba(92, 168, 214, 0.22)`): The active experience tab. A ring, not a lift.

### Named Rules

**The Lake Lift Rule.** When a surface lifts, the shadow is `0 18px 40px rgba(46, 126, 174, 0.1)`. It is wide, faint, and lake blue. It may sit under cards. A gray or black drop shadow is out.

## Shapes

The sheet uses a gentle corner, 18px, on education panels, the experience detail, and project rows. The MN mark and the contact icons use 10px. Experience tabs use 12px. The mobile menu uses 14px.

Pills, a 999px radius, are the exception. They are the primary button, the ghost button, the skill chips, the menu button, and the START button. Cards, tabs, and the mark are not pills.

Edges are a 1px sky hairline, except buttons, which use a 1.5px Lake Ink stroke.

### Named Rules

**The Pill Exception Rule.** Fully round corners belong to actions and skill tags. Panels, project rows, tabs, and the MN mark keep their softer corners.

## Components

Controls are quiet. The page reads as a document. Pills are the small exception for actions and skill tags. Hover shifts a color or a border. Nothing on the briefing page lifts on hover.

### Buttons

- **Shape:** Pill (999px). Padding 0.78rem 1.15rem. Plus Jakarta Sans, weight 800. Stroke 1.5px Lake Ink.
- **Primary:** Lake Ink fill, Paper Sky text. Hover and keyboard focus fill it with Daylight Blue, and the stroke follows.
- **Ghost:** Cloud White fill, Lake Ink text and stroke. Hover and keyboard focus turn the stroke Mid Sky and the text Daylight Blue.
- **Focus:** These two buttons have no authored focus ring. The color change above is the state the page defines.

### Chips

- **Style:** Cloud White, sky hairline, pill, padding 0.32rem 0.75rem, 0.88rem type at weight 650.
- **State:** No selected state. A chip names a tool. It is not a filter and not a button.

### Cards / Containers

- **Corner Style:** 18px.
- **Background:** Education panels are Cloud White at 72% opacity, padded 1.15rem 1.2rem. The experience detail and project rows are solid Cloud White.
- **Shadow Strategy:** None on the card today. The lake lift may be added. See Elevation & Depth.
- **Border:** 1px sky hairline. A project row's border shifts to Mid Sky on hover.
- **Internal Padding:** Project rows use 1.2rem 1.3rem. The experience detail uses 1.3rem 1.4rem. Dates and the outbound link are Daylight Blue. Supporting prose is Shore Mist.

### Navigation

- **Bar:** Sticky, 72px, Paper Sky at 86% opacity, 16px blur, sky hairline along the bottom.
- **Mark:** 42px tile, 10px corner, Logo Sky fill, Deep Lake letters, weight 800, 0.85rem.
- **Links:** Plus Jakarta Sans, weight 700, Shore Mist at rest. Hover and the current section turn Lake Ink.
- **Small screens:** Below 860px the links collapse. The menu button is a pill. The open list is Cloud White, 14px corner, sky hairline, and the lake lift.

### Experience tabs

A vertical list of text buttons. Inactive tabs are transparent, with Shore Mist type and the place name in Lake Ink. The active tab is Cloud White with a 12px corner and a 1px hairline ring. They are not pills.

### START screen

The door. Full viewport, a vertical sky from `#cfeaf8` through `#a9d8f0` at 55% to `#8ecceb`. Three white clouds drift 18px, on cycles of 18s, 22s, and 20s. The title is Fraunces in Deep Lake, with a 2px white text-shadow. The kicker is Daylight Blue, uppercase, tracking 0.18em. Subtitle and hint are Rain. The bottom links are Deep Entry, divided by `#3d7ea3`.

The START button is its own control: Entry Water fill, white type, pill, padding 0.95rem 1.8rem, 1.15rem type, weight 800, tracking 0.18em, and the entry cast. It pulses 5px on a 1.8s ease. Hover and focus use Deep Entry and a 3px white outline, 3px outside the pill. Leaving fades the screen over 0.45s. When the visitor prefers reduced motion, the drift, the pulse, and that fade turn off.

## Do's and Don'ts

### Do:

- **Do** keep the ground on Paper Sky and the reading text in Lake Ink.
- **Do** use Fraunces for the name and section titles, and Plus Jakarta Sans for the evidence, labels, and buttons.
- **Do** keep the sheet: a 180px label column, 18px panels, and a 1px sky hairline.
- **Do** limit pills to buttons and skill tags.
- **Do** use the lake lift when a surface needs to rise. Cards may take it.
- **Do** keep Daylight Blue for the emphasized name, links, project numbers, and icons.

### Don't:

- **Don't** build a dark analytics dashboard: no black canvas, no neon chart colors, no dense instrument panels.
- **Don't** set the hero name in Plus Jakarta Sans, or the body copy in Fraunces.
- **Don't** fill briefing-page buttons with Daylight Blue at rest. That color is the hover and the accent.
- **Don't** add decoration beyond the sky grid, the hairline, and the clouds on the START screen.
- **Don't** promote the unused `--blue` value (`#89c9e8`) into a new accent. It is declared and paints nothing.
