# v1.1 screenshots to capture

The landing page (`index.html`) was updated for the v1.1 release, but app
screenshots cannot be captured automatically. The existing v1.0 PNGs are
reused as placeholders where they still make sense. Capture the screens below
and drop them into this `screens/` folder, then swap the `src` in `index.html`
at the spots marked with `<!-- v1.1 SCREENSHOT NEEDED ... -->` comments.

Use the same device frames / aspect ratios as the existing images so the
layout and CSS stay intact (iPhone portrait for `iphone-*.png`, Apple Watch
for `watch-*.png`).

## iPhone (replaces / adds to `iphone-*.png`)

1. **`iphone-analysis.png`** (REPLACE) — the new Expert Analytics screen:
   pacing variability (CV), run-fade index, aerobic decoupling, training-load
   PMC (CTL/ATL/TSB), weakest-station ranking. The current file is the old
   v1.0 analysis screen.
2. **`iphone-coaching.png`** (NEW) — the plain-language Coaching Summary card
   ("what to focus on") + plan-vs-actual overlay.
3. **`iphone-detail-roxzone.png`** (NEW, optional) — segment breakdown showing
   runs + stations + RoxZone transitions as separate splits with transition
   grades (elite/good/fair/slow).

## Apple Watch (replaces / adds to `watch-*.png`)

4. **`watch-mode-select.png`** (NEW) — start screen mode picker:
   Competition / Pace / Train.
5. **`watch-pace-banked.png`** (NEW) — Pace Control live banked-time glance
   (+0:18 ahead / −0:25 behind) with the per-km pace.
6. **`watch-roxzone.png`** (NEW) — RoxZone transition clock between segments
   (two-tap model, "jog, don't walk" state).
7. **`watch-hrzone.png`** (NEW) — heart rate in zone color with the 5-zone
   gauge (Z1 gray → Z5 red).
8. **`watch-training.png`** (NEW) — a training interval timer
   (AMRAP / EMOM / Tabata / For Time) with round count.
9. **`watch-station-division.png`** (NEW, optional) — station card showing the
   division/gender weight, reps/distance and wall-ball target height.

## Still valid from v1.0 (no recapture needed)

- `iphone-summary.png`, `iphone-history.png` — still accurate (mode tags are a
  nice-to-have refresh, not required).
- `photocard.png` — still accurate.
- `watch-start.png`, `watch-run.png`, `watch-station.png`,
  `watch-records.png`, `watch-splash.png` — reused as placeholders for the new
  watch captions until the captures above land.
