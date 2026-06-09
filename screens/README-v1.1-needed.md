# Screenshots — v1.1 status

**Status: the landing page now ships the real v1.1 visuals.** They were sourced
from the App Store submission assets in the app repo at
`roxrec/ios/appstore/out/` and copied into this folder.

## Live on the landing page (`index.html`)

### iPhone — App Store screenshot filmstrip (`.shots-strip`)
These are the polished App Store marketing frames (headline + device + brand
baked in, 1290×2796), shown full-bleed in a horizontal filmstrip:

| File | Screen |
|---|---|
| `iphone-pace.png` | Pace Control — goal time, fatigue-adjusted paces, banked time |
| `iphone-roxzone.png` | Competition — live RoxZone transition clock, ELITE grade |
| `iphone-coaching.png` | Coaching Summary — 21 metrics → plain-language verdict |
| `iphone-training.png` | Training — timers, single station, compromised run, simulation, plan |
| `iphone-hrzones.png` | 5 lactate-threshold HR zones from a guided field test |

### Apple Watch — raw screen captures (`.watch-frame`)
Raw watch UI (410×502), dropped into the site's watch mockups:

| File | Screen |
|---|---|
| `watch-modes.png` | Mode picker — Competition · Pace · Train |
| `watch-active.png` | Live run — pace, total, HR + zone |
| `watch-roxzone.png` | RoxZone transition clock, ELITE |
| `watch-pace.png` | Pace banked time — +0:18 ahead of plan |

### Hero + photo card (still valid v1.0 raw captures)
- `iphone-summary.png`, `iphone-history.png` — hero phone mockups.
- `photocard.png` — Photo Record Card section.

## Optional future polish
- The iPhone filmstrip uses **marketing mockups**, not raw simulator captures.
  If you later want raw iPhone screens (status bar + real data) inside device
  frames, capture them from the simulator and re-introduce the framed-grid
  layout. Not required — the current filmstrip is the App Store-quality version.
- Orphaned v1.0 placeholders no longer referenced: `iphone-analysis.png`,
  `iphone-detail.png`, `watch-start.png`, `watch-run.png`, `watch-station.png`,
  `watch-splash.png`, `watch-records.png`. Safe to delete.
