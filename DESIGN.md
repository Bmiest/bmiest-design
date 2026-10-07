---
name: bmiest design language v2
description: The shared language of the bmiest family (stream overlay, bmiest.be, wishlist dashboard) and of Race to Dutch First, which shares the language but not the brand.
colors:
  ink-900: "#0a0b0d"
  ink-850: "#0e1014"
  ink-800: "#131519"
  ink-750: "#171a1f"
  ink-700: "#1e2228"
  ink-600: "#2a2f37"
  ink-500: "#3a414b"
  ink-400: "#5b6470"
  ink-300: "#818b98"
  ink-200: "#a8b1bc"
  paper: "#eef1f5"
  paper-dim: "#c9d0d8"
  jade: "#3fd9a4"
  jade-deep: "#1f8d68"
  jade-ghost: "rgba(63,217,164,.13)"
  gold: "#d8b263"
  rose: "#d98b8b"
  live-red: "#c93339"
  track: "rgba(238,241,245,.08)"
  void-glow: "rgba(150,90,255,.32)"
  hero-dusk: "#1b1030"
  hero-deep-teal: "#0d1a1c"
typography:
  display:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "clamp(44px, 6.6vw, 88px)"
    fontWeight: 800
    lineHeight: 0.92
    letterSpacing: "-.03em"
  headline:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "clamp(24px, 2.6vw, 32px)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-.01em"
  headline-sub:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "clamp(20px, 2vw, 24px)"
    fontWeight: 800
    lineHeight: 1.05
  lead:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.5
  pick-name:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.1
  ribbon:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "18px"
    fontWeight: 600
  body:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  button:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "15px"
    fontWeight: 800
    letterSpacing: ".1em"
  loot:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    letterSpacing: ".08em"
  bug:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "14px"
    fontWeight: 800
    letterSpacing: ".1em"
  label:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "11px"
    fontWeight: 700
    letterSpacing: ".12em"
  label-micro:
    fontFamily: "'Outfit', 'Segoe UI', system-ui, -apple-system, sans-serif"
    fontSize: "10px"
    fontWeight: 700
    letterSpacing: ".18em"
  numeric:
    fontFamily: "'JetBrains Mono', 'Cascadia Mono', Consolas, monospace"
    fontSize: "13px"
    fontWeight: 400
    fontFeature: "tnum"
rounded:
  none: "0px"
  pill: "999px"
spacing:
  gutter: "24px"
  gutter-phone: "16px"
  gutter-narrow: "12px"
  section: "40px"
  section-phone: "32px"
  card-gap: "16px"
  bar: "40px"
  bar-phone: "34px"
  ticker: "52px"
components:
  bug-live:
    backgroundColor: "{colors.live-red}"
    textColor: "{colors.paper}"
    typography: "{typography.bug}"
    rounded: "{rounded.none}"
    padding: "0 18px"
    height: "40px"
  bug-mark:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
    rounded: "{rounded.none}"
    size: "40px"
  bug-name:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.paper}"
    typography: "{typography.bug}"
    rounded: "{rounded.none}"
    padding: "0 22px"
    height: "40px"
  bug-slot:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.paper-dim}"
    typography: "{typography.bug}"
    rounded: "{rounded.none}"
    padding: "0 18px"
    height: "40px"
  bug-day:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
    typography: "{typography.bug}"
    rounded: "{rounded.none}"
    padding: "0 18px"
    height: "40px"
  lang-block:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.ink-300}"
    rounded: "{rounded.none}"
    padding: "0 14px"
    height: "40px"
  lang-block-active:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
  switch-block:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.ink-300}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0 14px"
    height: "32px"
  switch-block-active:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
  strip-key:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.ink-200}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0 11px"
    height: "30px"
  strip-value:
    backgroundColor: "{colors.ink-800}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "0 20px 0 11px"
    height: "30px"
  button-primary:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: "0 26px 0 20px"
    height: "52px"
  button-primary-live:
    backgroundColor: "{colors.live-red}"
    textColor: "{colors.paper}"
  loot-row:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.paper}"
    typography: "{typography.loot}"
    rounded: "{rounded.none}"
    padding: "0 26px 0 18px"
    height: "52px"
  pill:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.ink-200}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "6px 15px 6px 11px"
  pill-jade:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.jade}"
  ribbon:
    backgroundColor: "{colors.ink-800}"
    textColor: "{colors.paper}"
    typography: "{typography.ribbon}"
    rounded: "{rounded.none}"
    height: "46px"
  ribbon-outline:
    backgroundColor: "{colors.ink-600}"
  ribbon-outline-lead:
    backgroundColor: "{colors.gold}"
  pick:
    backgroundColor: "{colors.ink-800}"
    textColor: "{colors.paper}"
    typography: "{typography.pick-name}"
    rounded: "{rounded.none}"
    height: "60px"
  pick-active:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.jade}"
  race-track-segment:
    backgroundColor: "{colors.track}"
    rounded: "{rounded.none}"
    height: "7px"
  meter:
    backgroundColor: "{colors.track}"
    rounded: "{rounded.none}"
    height: "10px"
  ticker:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.paper-dim}"
    height: "52px"
  ticker-label:
    backgroundColor: "{colors.jade}"
    textColor: "{colors.ink-900}"
    padding: "0 20px"
  boss-head:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.ink-400}"
    size: "40px"
  panel:
    backgroundColor: "{colors.ink-800}"
    rounded: "{rounded.none}"
    padding: "16px 18px 18px"
  drop-panel:
    backgroundColor: "{colors.ink-850}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
  popover:
    backgroundColor: "{colors.ink-750}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
---

# Design System: bmiest design language v2

<!-- The family record. Rewritten 2026-10-08 from the four shipped products, replacing the copy of the race
     site's DESIGN.md that stood here since 2026-10-04 (3d7905c, 830afa0):
       - Stream overlay      Bmiest/bmiest_wow_streaming_theme   streamoverlay.bmiest.be   DESIGN.md as of #5-#9
       - bmiest.be           Bmiest/bmiest_landing               bmiest.be                 DESIGN.md as of #3
       - Wishlist dashboard  Bmiest/bmiest_wowaudit_wishlist_updater  wishlistupdater.bmiest.be  DESIGN.md as of #16
       - Race to Dutch First reniersworx/racetodutchfirst (private)   racetodutchfirst.nl  DESIGN.md as of #74, site as of #86
     This file holds only what is shared. Each product keeps its own DESIGN.md with [family] and [product]
     tags; a [family] rule there must match this file, and this file wins when they disagree.
     A part becomes [family] once two products ship it. A part one product ships and others should take is
     listed under "Offered components" with its source; take its spec from that product until a second one ships it. -->

## Overview

**Creative North Star: "The Raid on the Broadcast"**

The language of a raiding streamer's broadcast, carried onto every page the family runs. It started as the stream overlay and grew into a poster on the race site; everything since speaks it. The grammar comes from the broadcast and from the game: a **broadcast bug** of flush square blocks crowns every page, an **edge-to-edge ticker** closes the first view, standings are **ribbons** like a raid's nameplates, progress is a **health bar cut into one segment per boss**, and the art is **the boss itself**, cut out and standing in a jade and void glow with nothing drawn on it.

Everything sits on flat near-black ink: no rounded cards, no drop shadows, no glass. Shape comes from one cut, the **slant on the trailing edge** of every ribbon, pill, button, bar, chip and tile. Colour is scarce and always means something: jade is the brand and what is selected or OK, gold is earned, red is on air, rose is failed or stale, and guilds and classes bring their own colours as game data. The pages are loud at the top and dense, honest data below, where the marks explain themselves.

Each product is a different room in the same house: the overlay is the broadcast, bmiest.be is the Adventure Guide that opens onto the tools, the wishlist is the operator's raid-night sheet, and Race to Dutch First is the raid poster for the Dutch community, sharing the language but not the brand.

Confirmed rejections (direction history 2026-10-03, and since): the generic dark data dashboard ("too generic, AI-looking"), a sports-broadcast theme laid on top ("still a dashboard, not WoW"), a link-in-bio column, and a hero over a project-card grid. More gamer-like is welcome; a dashboard is not.

**Key Characteristics:**
- Flat ink ramp, Outfit + JetBrains Mono, jade + gold, from one tokens.css copied byte for byte.
- The right-edge slant on a named scale; square corners everywhere else; the bug, switches, strips and ticker are flush square blocks.
- Colour as meaning: jade = brand, selected, OK; gold = earned; live-red = on air; rose = failed or stale; guild and class colours = game data.
- The work shown running: live data with an honest timestamp, real renders and real screenshots, never a mock-up of itself.
- Motion only when the data moves.
- Every string in Dutch and English; game names never translated.

## Products and brand

| Product | Brand | Mode | Room |
|---|---|---|---|
| Stream overlay (OBS sources + showcase page) | bmiest | Experience (on stream), Persuade (showcase) | character select in front of the current boss |
| bmiest.be | bmiest | Persuade | the Adventure Guide: encounter list, one entry on the stage, loot as actions |
| Wishlist dashboard | bmiest | Operate | the raid-night plan: a tile per boss, the best upgrade in gold |
| Race to Dutch First | **neutral** | Read / Operate | the raid poster: the leader's boss as hero, ribbons, race tracks |

The bmiest mark (the drawn broadcast/cast mark on a slanted jade block) appears on bmiest products only. Race to Dutch First carries no bmiest mark, name or link in its design; the privacy page names "bmiest" as its operator, which is a legal fact, not branding.

## Colors

A near-black ink ramp with one cool jade voice, one warm gold voice, red only on air, rose for trouble, and the game's own colours where the game would put them.

### Primary
- **Mistweaver Jade** (jade): the brand and what is selected, active or OK. Bug mark and day blocks, the active block of any flush switch, a selected pick's outline and subline, the primary button, the ticker label and its 2px top edge, section-head caps, the kill check, links, the disclosure chevron, the CE marker, and focus rings (2px outline, 3px offset). Its ghost (jade-ghost) only for link underlines and text selection.
- **Deep Jade** (jade-deep): a quieter jade for finish lines and season ends that should not read as live (the race's CE line and season-end line, the wishlist's viewed history row).

### Secondary
- **Podium Gold** (gold): earned, and nothing else. The race leader, the race's first kill and the winner; a new best on the overlay and in the race's news; the single best upgrade on the wishlist; Cutting Edge and a first Dutch kill on bmiest.be.

### Tertiary
- **Broadcast Red** (live-red, #c93339): on air, and nothing else. The LIVE block in the bug, the primary button while the channel is live, a live ring on a stream's head tile, a "n live" block. Paper on it reaches 4.6:1. Red is a ground or a ring, never small text on ink: 10px red on ink-900 reaches only 3.8:1 (a defect found on bmiest.be). Never on a page that is itself the stream.
- **Faded Rose** (rose): failed, error or stale. A failed run (rose block with ink-900 text), an error panel's 1px border, a staleness warning. Never red.

### Neutral
- **Raid Night Black** (ink-900): page ground, the bug's name block, the ticker band, inactive switch blocks, ink text on jade, gold and class colours.
- **Table Ink** (ink-850): wells, cells, tile bodies, drop panels.
- **Panel Ink** (ink-800): ribbon and pick bodies, panels, strip values.
- **Raised Ink** (ink-750): pills, loot rows, strip keys, boss-head tiles, a selected pick's body, popovers.
- **Rule Ink** (ink-700): 1px borders, rules, chart grids, hairlines, meter tracks on dense rows.
- **Outline Ink** (ink-600): the 1px slanted outline of ribbons and picks, loot-row hover, dashed empty states.
- **Muted Ink** (ink-500 / ink-400): plain bars, initials, a pick's outline on hover (ink-400).
- **Caption Grey** (ink-300): secondary meta, axis labels, inactive switch text, hints.
- **Soft Grey** (ink-200): pill text, strip keys, table heads, timestamps.
- **Paper** (paper, #eef1f5): primary text. Never pure white.
- **Faded Paper** (paper-dim): leads, body copy, ticker body.
- **Track** (track): the unfilled part of a meter or race track, paper at 8%.

### Hero atmosphere
- **Void Glow**, **Hero Dusk**, **Hero Deep Teal**, plus a jade radial: only behind boss art. A violet radial and a jade radial (jade at 20-22%) behind the boss, over a dusk-to-teal-to-ink linear where a full hero needs it, faded into ink-900. Product values differ (void at 24% on the overlay, 32% on the race hero, 28% behind an earned Hall of fame stage); they are tuning, not rules. Web only: the overlay's stream pages carry no gradients.

### Game data colours
Guild colours (from the race's guilds.toml) and WoW class colours are game data, held in product code, not in tokens.css. They mark only their guild or class: a rank block, a track fill, a line, a chip, a meter; class colours as the 3px foot bar of a raid-frame cell or the class ribbon's key block. Guild colours stay clear of jade and gold. Priest's pure white is drawn as paper. Monk green sits near jade and is accepted only where it can't be read as the brand.

### Named Rules
**The Gold Is Earned Rule.** Gold marks something earned: a leader, a first, a winner, a new best, the best upgrade. A tag, a hover, a progress state, a late note or a project label is never gold, and something that doesn't count earns no gold (a raid outside the race gets a grey pill).

**The Red Means On Air Rule.** Broadcast red appears only while a channel is really live, from a fresh check, and every red mark goes when it isn't. Raiding itself is jade; a failure is rose.

**The Owner's Colour Rule.** A guild's or class's colour marks that guild or class and nothing else; a guild's best effort is drawn in its own colour.

**The Quiet Timestamp Rule.** The update line says when the data was fetched ("Bijgewerkt om 13:42"), in quiet grey, never the next run and never coloured. Only data that is older than its source promises (a failed fetch, a stale Raider.IO profile) turns rose, and then with words that say so.

## Typography

**Display Font:** Outfit (with Segoe UI, system-ui)
**Label/Mono Font:** JetBrains Mono (with Cascadia Mono, Consolas), tabular figures

**Character:** One geometric sans carries everything from the poster caps to 10px labels; the mono is reserved for numbers.

### Hierarchy
- **Display** (display): once per page, uppercase, balanced; the second half may be jade. Products set their own size (88px on the race hero, 112px for "BMIEST").
- **Headline** (headline): section heads and entry titles, uppercase, behind a 14px slanted jade cap.
- **Headline sub** (headline-sub): one step down, behind an 11px cap.
- **Lead** (lead): one line under a display, max 34-40ch, paper-dim; 17px on phones.
- **Pick name** (pick-name): names in a pick list; 15-16px on phones.
- **Ribbon** (ribbon): names on ribbons; 16px on dense lists, 14px under 400px.
- **Body** (body): copy and ticker items; 14px on phones.
- **Button / Loot** (button, loot): the primary and the loot rows, uppercase.
- **Bug** (bug): the bug's blocks, uppercase; LIVE at 13px/.14em; 12-13px on phones.
- **Label** (label): pills, switch blocks, strip keys, table heads, nav heads; uppercase. Pills run 11-12px across products (race 12px/.1em).
- **Label micro** (label-micro): role rows, tags, badges; uppercase.
- **Numeric** (numeric): every number read as a value or compared; products add larger numeric steps (the race board's 32px).

### Named Rules
**The Poster Voice Rule.** Display and headlines are Outfit 800 uppercase with tight tracking. Only the bug, buttons, switch blocks, strip keys and a few rank and count blocks share that weight.

**The Mono Number Rule.** A number a visitor compares or reads as a value (kills, ranks, pulls, dates, percentages, ilvl, countdowns) is JetBrains Mono with tabular figures.

**The Raider's Numbers Rule.** State is said the way raiders say it: kills out of the counted bosses and what was left of the current boss after the best pull ("6/8 · nog 69,8%"), never a fractional position ("6,3"). Fractions only drive drawings (track fill, line height).

**The No Caption Rule.** A section carries no caption explaining what is visible; the marks explain themselves (a key with the real marks, a sort chevron, "bij alle N kills" in place). Replaces the earlier One-Line Caption Rule (race, 2026-10-06).

## Layout

One container per page, 1320-1360px max, 24px gutters (16px under 720-900px, 12px under 400px). Pages open on a stage between the bug bar and the ticker, sized to the first viewport; below it sections stack 40px apart (32px on phones). Card grids auto-fill with 280-340px minimums and 16px gaps. Labels wrap rather than cut a number off. Everything works at 360px (bmiest.be at 350px).

Stage art follows the boss art rules (below): it takes the open field, never sits behind text it would hurt, and becomes a band above the title on narrow screens.

## Elevation & Depth

Flat. Depth comes from the ink ramp (ink-900 ground, ink-850 wells, ink-800 bodies, ink-750 raised chips), 1px ink-700 lines, and on a stage from the boss standing in its glow. `box-shadow` is a drawn line only: the 2px paper ring around the LIVE dot, a 2px live-red inset ring on a live head tile, a 1px inset outline in a guild colour or gold, never elevation.

### Named Rules
**The Flat Ink Rule.** Surfaces separate by tone and 1px lines, never by shadow or blur.

**The One Float Rule.** The single exception: a popover that floats over content it doesn't belong to (the race's kill-rank popover) casts one shadow, `0 8px 20px -6px rgba(0,0,0,.7)`, on ink-750 with a 1px ink-500 border and a caret. Panels that open under the bar (the Streamers panel) stay flat.

## Shapes

Corners are square. The signature is the right-edge slant, `clip-path: polygon(0 0, 100% 0, calc(100% - N) 100%, 0 100%)`. Outlines are a slanted outer clip one pixel larger than the inner one. The only round things are dots (the LIVE dot, legend dots, chart nodes).

### Slant scale
N grows with the element. Pick the step for the role, not a new number.

| N | Role |
|---|---|
| 2-3px | hairline marks: a race track under a ribbon (2px), guild chips and standings rank blocks (3px) |
| 4px | the subsection cap, 28px boss heads |
| 5px | the section-head cap, tags, lane race-track segments, the footer mark |
| 6px | pills, meters, bars, 40-52px boss heads, raid-frame cells, step numbers |
| 8px | strip values, the play block, a boss tag's last block |
| 10px | inner bodies: ribbon key blocks, guild blocks, pick head tiles, caption plates |
| 11px | ribbon and pick outlines |
| 12px | buttons: the primary and loot rows |
| 16px | poster plates (bmiest.be's tool plates) |
| 22px | frames: screenshot frames, specimen panels, the rcard notch |

The overlay's primary button moves from 11px to 12px at its next change, so the button step is one value across products.

### Flush blocks
The broadcast bug, the language switch, any view switch or tab row, key/value strips and the ticker are the deliberate exception: flush, square, gapless blocks. A selected block is solid jade with ink text.

### Marks
Icons and marks are drawn SVG in one stroke family (2px strokes; line caps are not yet settled across products: bmiest.be draws square, the overlay round): check (jade, a kill), star (gold, a first), trophy (gold, a winner), chevron (jade, disclosure; 7px, -45deg closed, 45deg open), out-arrow, play, cast/broadcast, Twitch, YouTube, clips, GitHub. In CSS cells they are SVG masks over a background in the meaning colour. Empty states are dashed (1px ink-600 or ink-750); every other border is solid.

### Named Rules
**The One Slant Rule.** Slants go down and to the right, on the trailing edge only. A slanted element never also gets rounded corners.

## Motion

Two curves in tokens.css: `--ease` (cubic-bezier(.22,.61,.36,1)) for hover and small state changes at `--t-fast` 160ms, and `--ease-out` (cubic-bezier(.16,1,.3,1), no bounce) for anything that travels: a stage wipe, a track running, a row sliding, a card arriving. `--ease-out` is used by the race site and bmiest.be today and still has to be added to tokens.css.

### Named Rules
**The Data Moves It Rule.** A page doesn't move on load; it moves when the data does, once. A track runs from its old to its new position, swapped rows slide (FLIP, 650ms), only the new stretch of a line draws, a new kill lights in the ticker, a new boss crossfades in. Constant motion is limited to the LIVE dot and the ticker.

**The Along the Slant Rule.** Things that enter travel along the family slant: a wipe's leading edge leans down and to the right (bmiest.be's stage wipe, 620ms; the race news card, 420ms).

**The Reduced Motion Rule.** Under `prefers-reduced-motion` only colour cues remain: the ticker becomes a static scrollable row, swaps happen without travel, counts land at their final value.

**The Bitrate Rule.** On stream pages (overlay OBS sources): no gradients, no animation across the full width, no pure white; canvas 2560×1440.

## Components

### Broadcast bug
A row of flush square blocks at 40px (34px on phones), no gaps, each optional, always in this order:
1. **LIVE**: live-red, pulsing dot with a 2px paper ring, 13px/.14em; hidden unless live.
2. **Mark**: 40px jade block with the drawn mark (bmiest products only).
3. **Name**: ink-900, bug type ("bmiest", "Race to Dutch First"); jade on hover when it links.
4. **Slot**: context on ink-750 or jade (the guild "Kelderklasse · EU-Draenor"; the wishlist's run status: jade OK, rose FAILED, ink-750 unknown).
5. **Day**: jade (the race's "Dag N", bmiest.be's raid days).

The quiet update line sits beside it. Blocks drop from the right on narrow screens (realm first, then slot, then day).

### Language switch
NL | EN as two flush blocks at the bug's height, 13px/800/.12em; active solid jade with ink text, the other ink-900 with ink-300 (paper on hover). The language is the stored choice, else the browser's (Dutch for nl-*), else the product default (Dutch on the race site, English elsewhere; the overlay's OBS sources take `?lang=`).

### Flush switch and tabs
The language switch's construction one step smaller for views and periods: 32px blocks, 12px/800 caps (the race's Grafiek | Plaatsen | Replay | Ronde; the wishlist's Heroic | Mythic tabs at 40px inside a 1px ink-700 frame). Real tablist semantics; the row scrolls sideways on phones.

### Key/value strip
Flush blocks at 28-30px: a key (ink-750, label type at 800, ink-200; or solid jade for a highlighted key like the overlay's "PGM") and a value (ink-800, paper, an 8px trailing slant on the last block, ellipsis). bmiest.be's abilities and the overlay's tally strips are this component; live values replace static fallbacks, earned words in them go gold.

### Primary button
Solid jade, ink text, button type, 52px tall (48px allowed on dense pages), a 12px trailing slant and a 20px drawn icon; hover turns it paper. One per view. While the channel is live a Watch button turns live-red with paper text ("Live now · watch"; paper with red text on hover). An outbound link gets a 16px out-arrow after its label.

### Loot row
The secondary action: an ink-750 chip at the primary's height and slant, loot type in paper, an 18px jade drawn icon; hover lifts it to ink-600 with jade text. Loot stacks full width under the primary on wide and phone layouts and wraps in a row between.

### Pills and copy button
Slanted ink-750 chips in label type, uppercase; jade text for a positive marker (CE, Demo mode), gold text with a star only for something earned ("Eerste kill · dag N"), ink-300 for a neutral status. A pill can be a button (jade text, ink-700 on hover); the copy button turns solid jade with ink text once copied.

### Ribbon
A 1px slanted ink-600 outline (gold for a leader) around an ink-800 body, a square key block on the left (the rank in mono 20px/800 ink-900 on the guild colour, or a micro label on ink-700, or a class colour with ink text), then the name in ribbon type with an ellipsis. Links go jade on hover.

### Pick
The ribbon as a choice list (the overlay's character select, bmiest.be's encounter list): 60px, a 60px slanted head tile (an avatar, a head crop at `object-position: 50% 0`, or a project mark), the name in pick-name type over a 12px ink-300 subline. Hover lifts the outline to ink-400, focus to paper; the chosen pick has a jade outline, an ink-750 body and a jade subline. A live stream's head gets a 2px live-red inset ring.

### Race track
Progress as a boss health bar: one slanted segment per boss of the tier, 3px apart, so length equals position. Killed bosses fill in the owner's colour, the current one as far as its best pull ((100 - best %) / 100); empty segments are track, the last (the finish) jade at 20%. Under a ribbon it hangs like a nameplate's health bar: 7px tall, 2px slant, ending where the ribbon's slant ends; in lanes 14-20px with a 5px slant. Driven by one number `--p` minus each segment's `--i`.

### Meter
A single 10px slanted bar (5px in dense cells): track behind, fill in jade or the owner's colour, gold only on the earned best.

### Kills ticker
A 52px ink-900 band spanning the viewport, a 2px jade top edge only, a solid jade label block flush left ("Laatste nieuws", "Mythic kills", "Alerts"). Items: a mono time or tag, the sentence in paper-dim with the name bold (paper, or the guild's colour), gold for a first or a new best, jade for an overtake; a 1px ink-700 rule between items. The list renders twice and slides one width at a constant speed of about 58px a second, set from the content's length (`--tk-run`), so a short list doesn't race and a long one doesn't crawl. It pauses on hover and focus, becomes a static scrollable row under reduced motion, hides when there is no data, and a 64px fade hides its right edge.

### Section head
Headline type behind a slanted jade cap (14px wide, 0.9em tall, 5px slant), 18px above the content, no caption. Subsections use headline-sub behind an 11px cap (4px slant). A folded section is never dressed as a section head.

### Folds
A `<details>` between 1px ink-700 hairlines: the drawn jade chevron, the title (paper, jade on hover) and a 14px ink-300 hint. Every disclosure uses the same chevron, never the browser triangle.

### Boss head
A slanted ink-750 tile (28-76px) showing the top of the boss's cut-out (`object-position: 50% 0`), or the initial in ink-400 800 when there is no art, so heads line up. A boss nobody has beaten is a dark silhouette.

### Panels
Square ink-800 panels with a 1px ink-700 border; interactive ones lift to ink-750 with an ink-600 border on hover. A winner is the panel with a 2px gold border and a drawn trophy. An error is the panel with a 1px rose border.

### Drop panel
What opens from the bar (the race's Streamers panel): flat ink-850 under the bar, 1px ink-700 border, no shadow, the bar's full width on phones. Its trigger is a flush block in the bar, jade with ink text while open.

### Popover
The One Float Rule's popover: ink-750, 1px ink-500 border, one shadow, a caret, label-type title and mono values. Opens on hover, focus or tap; Escape or a tap elsewhere closes it. Its trigger reads as openable: a dotted ink-400 underline and a 10px chevron.

### Footer
A 1px ink-700 rule, then the name or mark with a quiet signature, uppercase links (13px/700-800, jade on hover; the current one paper with a 2px jade foot). A "to top" control is an ink-800 block with a 6px slant and a drawn chevron.

## Boss art

The boss is the family's hero art on every product.
- Self-hosted alpha cut-outs trimmed to the body, generated by the race site's boss-cutouts script with provenance embedded (`impeccable embed-prompt`) and mapped in `bossart.js`; other products keep a trimmed copy of that map.
- Nothing is drawn on the art. It stands in the hero glow, its feet faded by a mask.
- Never past 2x its natural height. A council shows both bodies, unless one is under 40% of its partner's height, which is dropped; a render cut off at the top is faded rather than shown as a flat crop.
- The current boss is real: the boss the guild (or the race leader) is on now, swapping as the data moves.

## Fonts and tokens

- **tokens.css** carries colours, type families, radii, spacing and motion, and is copied byte for byte between products. It loads no fonts.
- **fonts.css** self-hosts Outfit (300-800) and JetBrains Mono (400-700), latin + latin-ext woff2 under the SIL OFL, so a visit never asks Google. Introduced by the race site (#65, privacy); the other products still load Google Fonts through an `@import` at the top of the overlay's tokens.css and move to fonts.css at their next change.
- **holy** (#ffffff) exists in tokens.css for the overlay's v1 stream pages only; nothing on a web page uses it.

## Offered components

Shipped by one product, offered to the others. Take the spec from the source product's DESIGN.md until a second product ships it, then move it above.

| Component | Source | Fits |
|---|---|---|
| News takeover (card wipe on the slant, stamped tag, % count-down with HP chip, BOSS DOWN, shards) | Race #61, #83 | overlay alerts |
| Raid frame (Tanks / Healers / DPS rows, class-colour foot bar per cell) | Race #74 | overlay roster, wishlist team views |
| Current-boss card (rcard, 22px notch) | Overlay | race, bmiest.be |
| Tool plate (ribbon construction at poster size over a real shot) | bmiest.be #2 | design.bmiest.be |
| Design specimen (ink ramp, role tiles, ribbon, pill and type, drawn from tokens.css) | bmiest.be #1 | design.bmiest.be home |
| Boss tile (head strip over an upgrade list, best in gold) | Wishlist #8 | race Hall of fame |

## Do's and Don'ts

### Do:
- **Do** take colours, fonts, spacing and motion from tokens.css variables; keep tokens.css a byte copy.
- **Do** keep gold for what is earned, jade for brand and selection, red for on air, rose for failed or stale.
- **Do** pick slants from the scale and keep the bug, switches, strips and ticker flush and square.
- **Do** show the work running: live values with a quiet fetch time, real renders, real screenshots, specimens drawn from the tokens.
- **Do** let every live block fall back to static content when its fetch fails.
- **Do** move only when the data moves, along the slant, with `--ease-out`.
- **Do** draw marks as SVG in one stroke family, in the meaning colour.
- **Do** let a label wrap rather than cut a number off.
- **Do** ship every string in Dutch and English; game names are never translated.
- **Do** keep the CSP on the web products: script-src 'self', no inline styles; set custom properties with `style.setProperty()`; build DOM from external names without `innerHTML`.

### Don't:
- **Don't** add drop shadows, rounded cards, blur or glass (the one popover excepted).
- **Don't** put a coloured side stripe on cards, cells or rows (a raid-frame foot bar is not a side stripe).
- **Don't** use text glyphs (★, ✓, ▸, emoji) as icons or disclosure marks.
- **Don't** use gold for tags, hover, progress, lateness or project labels.
- **Don't** show LIVE, a live dot or any red unless a fresh check says live.
- **Don't** colour the update time; say staleness in words, in rose.
- **Don't** explain a section in a caption.
- **Don't** add bmiest branding to Race to Dutch First, or show the person behind bmiest anywhere.
- **Don't** build any of it as a generic dark dashboard.

## Migration from the products

What each product still has to change to match this file:
- **All but the race site:** self-host fonts (fonts.css) and drop the Google Fonts `@import` from tokens.css; add `--ease-out` to tokens.css.
- **Overlay:** primary button slant 11px → 12px; pick hover outline ink-500 → ink-400; ticker at a constant speed instead of a fixed 56s.
- **bmiest.be:** ticker at a constant speed instead of 9s per kill.
- **Wishlist:** refresh tokens.css (it predates Outfit 800 and `--live-red`); its "Figure Is Mono" rule is the Mono Number Rule.
- **Race:** none beyond the shared tokens change; its DESIGN.md's "byte copy" line now points at this file.
