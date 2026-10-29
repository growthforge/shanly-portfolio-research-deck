# Anti-slop QA: previews rebuilt after critique (28 Oct 2026, 20:55 GMT)

Hemanth rejected the first A (Board Pack) and B (Case Index) as "AI slop". Both rebuilt from scratch.

## Automated checks (both files and chooser)
- Em/en dash characters and entities: 0
- Costume grep (FIG, rotate, box-shadow, text-stroke, Google Fonts, Lucide, trackers, LinkedIn, certifications, buzzwords): 0 hits
- scrollWidth at 375px: 375 (A, B, chooser), with JS on and off. No page errors.
- JS off: mock-up shows static numbered list; B filter box stays hidden; all content readable.
- Colour: small text uses ink #1A1A18, mute #55524B (6.7:1), accent #A84A2F (5.2:1), forest #2F5D50 (6.8:1). #8C877C only on the dashed band border.
- Keyboard: skip link, visible focus ring, mock-up tabs with arrows, Home, End, roving tabindex, aria-live step count.
- Reduced motion: smooth scroll off. No animation.

## Scores (0 to 10)
| Criterion | A Evidence Cover | B Operator Index |
|---|---|---|
| 1 Fidelity to named refs | 8 (dhruv claim + contents rail + 01 marker; hero-15 stat strip; erbsu bordered cards; stats-bento for AirTM) | 9 (registry.directory mono rows, right-aligned meta, filter box, cream; erbsu quiet top) |
| 2 No AI costume | 9 | 10 |
| 3 Calm type hierarchy | 8 (one serif claim, serif only for titles and numerals) | 9 (sans heading, mono body, no serif) |
| 4 Honesty | 9 | 9 |
| 5 Mobile 375 | 9 | 9 |

No score below 8.

## Honesty notes
- Numbers used: 8 hours or 2 to 3 days to 1 to 3 hours; dozens of workflows; approx. 25% and 100+ cases; approx. 35% and 30+ entities; AirTM approx. 30%, 150 cases in 3 weeks, 95%+, approx. 25%. Nothing else.
- Orchestration has no number ("Pattern").
- Kuruvella adoption worded as "built in Excel, a tool the practice already had".
- Shanly ideas: every one carries the exact label, and each "before" says "Assumed starting point, to check with the team".
- Mock-up values (berth 14, MR-0001, 3 open, 5 closed) are labelled Sample data.
- Footer: own page, not official Shanly, does not work there; section 2 sources linked.
- Inferences to flag: BTF "Why" ("to get cases through faster") and Kuruvella "How" (macros for steps, dashboards for output) are framings of the stated facts, not new facts.

---

## C · Craft Mix (added 28 Oct 2026, about 23:59 GMT)

Hemanth asked for one page that mixes the researched components. C combines 21st hero-15, dhruvsinghal.codes, registry.directory, erbsu.com and 21st stats-bento. Borrow list: previews/MIX.md.

### Automated checks (preview-c.html, index.html, MIX.md)
- Em/en dash characters and entities (and box-drawing lines): 0. Section marker line is a CSS hairline.
- Costume grep (FIG, rotate, box-shadow, gradient, text-stroke, stamp, Google Fonts, Lucide, trackers, LinkedIn, certifications, buzzwords): 0 hits.
- scrollWidth at 375px: 375 with JS on, JS on with every case row opened, and JS off. No page errors. Chooser also 375.
- JS off: index rows are native details (first open, rest open on click or Enter); filter stays hidden; mock-up shows the static numbered list.
- Filter (JS on): "Own work" leaves 1 row; "All" restores 5. aria-pressed on each button.
- Contrast: ink 15.9:1, mute 7.1:1 on paper (6.5:1 on hover tint), accent text #A84A2F 5.2:1, forest 6.8:1, light text in the dark AirTM cell 10.6:1 or more. #C45C3E only on non-text marks.
- Keyboard: skip link, visible focus ring, summary rows focusable, mock-up tabs with arrows, Home, End, roving tabindex, aria-live step count. Reduced motion: smooth scroll off. Print: beforeprint opens every case.

### Scores (0 to 10)
| Criterion | C Craft Mix |
|---|---|
| 1 Fidelity to named refs | 9 (all five refs used where they are strongest, each named in MIX.md) |
| 2 No AI costume | 9 (no stamps, no tilt, no shadow, no pills; tags are dot-separated text) |
| 3 Calm type hierarchy | 9 (bold serif for claim, section and case titles only; mono for meta; sans for reading) |
| 4 Honesty | 9 (section 4 numbers only; orchestration is "Pattern") |
| 5 Mobile 375 | 9 (index meta drops under the title; cases go single column) |

No score below 8.

### Honesty notes for C
- Same allowed numbers as A and B, nothing added. MTest result reads "1 to 3 hours of supervised draft-and-review"; starting point "a full 8 hour day, or 2 to 3 days on larger projects".
- Kuruvella "Who uses it": "Built in Excel, a tool the practice already had, so there was no new software to adopt."
- Orchestration "Who uses it": "I do." Result: "Pattern: staged steps, a review gate and a full record." No number.
- BTF "Why: To get cases through faster" is a framing of the stated redesign fact, as in A and B.
- Index row meta labels ("Approx. 25% faster", "Approx. 35% less prep") are shortened restatements of section 4 results.

---

## D · Workspace, Linear + Notion mix (added 29 Oct 2026, about 00:30 GMT)

Hemanth rejected the paper direction. D is a light product workspace: shadcn sidebar shell, Notion document canvas, Linear issue rows, Raycast command filter, Stripe / Vercel proof chips, shadcn table and badges. Borrow list: previews/PRODUCT-UI-MIX.md.

### Automated checks (preview-d.html)
- Em/en dash characters and entities: 0. Google Fonts, Lucide, LinkedIn, buzzwords, trackers: 0 hits.
- scrollWidth equals viewport at 375, 768 and 1280, with JS on (every row opened at 375) and JS off. No page errors.
- JS off: command filter hidden; rows are native details (MTest open); mock-up shows the static numbered list.
- Filter (JS on): text "power bi" leaves 1 row; "Own work" leaves 1; no match shows the empty message; Esc clears; / focuses the input.
- Contrast: ink 16.0:1; mute #62666D 5.4:1 on #F7F8F8; meta #696E76 about 4.8:1; white on #5E6AD2 button 4.7:1; badge text 5.4 to 5.9:1 on their soft fills; green badge darkened to #276B43.
- Keyboard: skip link, focus ring in accent, summary rows focusable, mock-up tabs with arrows / Home / End and aria-live step count. Reduced motion: smooth scroll and chevron transition off. Print: sidebar, filter and buttons hidden, every row opened.
- Mobile (<768): sidebar stacks into a wrapped nav above the canvas; build list drops ID and date columns; property rows go single column.

### Scores (0 to 10)
| Criterion | D Workspace |
|---|---|
| Refs | 9 (each pattern traced to Linear, Notion, Raycast, Stripe, Vercel or a named component library) |
| No costume | 9 (no dark cosplay, no glow, no icons library, no fake app chrome beyond sidebar and breadcrumb) |
| Type | 9 (one sans family, two weights, mono only for IDs and meta) |
| Honesty | 9 (section 4 numbers only; orchestration is "Pattern") |
| Mobile | 8 (no horizontal scroll at 375; sidebar becomes a wrapped nav rather than a drawer) |

No score below 8.

### Honesty notes for D
- Same copy as C, nothing added. MTest: "a full 8 hour day, or 2 to 3 days on larger projects" to "1 to 3 hours of supervised draft-and-review".
- Kuruvella "Who uses it": "Built in Excel, a tool the practice already had, so there was no new software to adopt."
- Orchestration result: "Pattern", no number.
- Row IDs (HV-1 to HV-5) and status circles are layout only, not claims.
- Date column shortens BTF and Kuruvella to years (2023 to 2024, 2021 to 2023); full months are in the detail.
- Properties: "Builds with" shows five tools from section 4; "Education" names only the MSc.
- Ideas callout line ("These are ideas, not claims. I do not know Shanly's internal systems.") is new framing, not a fact; every idea keeps the exact illustrative label and "Assumed starting point, to check with the team".
- Mock-up values (berth 14, MR-0001, 3 open, 5 closed) marked Sample data.
