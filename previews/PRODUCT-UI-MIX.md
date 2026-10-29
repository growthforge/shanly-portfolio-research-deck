# Preview D · Workspace: product-UI borrow table (29 Oct 2026, about 00:30 GMT)

Hemanth rejected the paper / craft-mix direction (A, B, C) and asked for a mix of Linear, Notion "and much more", then asked to cover the component UI libraries too. D steals methods, not logos. System fonts only (Inter if installed, else ui-sans-serif / system-ui; ui-monospace for meta). No Google Fonts, no Lucide, no Shanly branding or colours. Light theme so it prints and emails well.

Posters for every reference: `design-pack/shots/product-ui/` (browser captures, 1280x800).

## Product sites

| Source | URL | Pattern borrowed | Where in D |
|---|---|---|---|
| Linear (product view) | https://linear.app/ | Issue rows: status circle, mono ID, title, right-aligned result and date; compact density; hairline borders; no shadows; lavender #5E6AD2 only on status, primary button and focus | Builds list (HV-1 to HV-5) |
| Linear (chrome) | https://linear.app/ | Pill primary button, ghost secondary | Hero CTAs, mock-up buttons |
| Notion | https://www.notion.com/ | Sidebar + document canvas; breadcrumb bar; page property rows; toggle blocks; callout | App shell, About properties, case detail pages (What / Why / How / Who uses it / Result), Ideas callout |
| Raycast | https://www.raycast.com/ | Quiet command input with a / key hint | Filter above Builds (JS only) |
| Stripe | https://stripe.com/ | Muted label over one tabular number | Three proof chips |
| Vercel | https://vercel.com/ | Monochrome whitespace; one bordered card with internal dividers | Proof card, contact cards |
| Height | https://height.app/ | Skipped: site no longer live | None |

## Component libraries

| Library | URL | Pattern borrowed | Where in D |
|---|---|---|---|
| shadcn/ui Sidebar | https://ui.shadcn.com/docs/components/sidebar | Workspace header block, group labels, items with counts, stacks on mobile | Left sidebar (Pages, Builds) |
| shadcn/ui Command | https://ui.shadcn.com/docs/components/command | Input with search glyph and kbd hint, segmented scope | Builds filter + provenance segment |
| shadcn/ui Badge / Table / Card | https://ui.shadcn.com/ | Outline and soft-fill badges; data table with muted header row; 1px border, 8px radius as the only container | Provenance badges (Client build / Employed role / Own work), AirTM table, all cards |
| 21st.dev | https://21st.dev/ | Command-K search pill + sidebar taxonomy; task-steps states (done / current / pending) | Filter bar feel, Sorbon mock-up step list |
| Magic UI | https://magicui.design/ | Timeline idea only, static (no glow, no particles, no motion) | How I work rail |
| Aceternity UI | https://ui.aceternity.com/ | Vertical timeline rail with small nodes (skip aurora, 3D) | How I work rail |
| HyperUI | https://www.hyperui.dev/ | Plain HTML badges, tables, description lists with no framework | Single-file build approach, tool badges |
| Cult UI / Tailark / Shadcnblocks | https://www.cult-ui.com/ · https://tailark.com/ · https://www.shadcnblocks.com/ | Looked at for list / table / sidebar blocks; nothing taken beyond what shadcn already gives | None |

## Deliberately not taken
Dark mode, gradients, glow, particles, marquee, 3D, logo clouds, avatar stacks, mascot icons, Lucide icon soup, marketing hero cosplay. Icons are CSS shapes (status circles, checkboxes, dots).
