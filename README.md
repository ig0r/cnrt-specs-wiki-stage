# cnrt-specs-wiki-stage

Staging build of the PennDOT **specifications** wiki: concept pages synthesized from PennDOT
Publication 242, Pavement Policy Manual (May 2015 Edition, Change No. 10), and Publication
408/2026 Specifications (Change No. 1).

Live: https://ig0r.github.io/cnrt-specs-wiki-stage/

| What | Where |
|---|---|
| Concept hierarchy (245 pages, root `penndot-pavement-policy-manual.html`, five top-level topics) | `index.html` |
| Pages added 2026-10-30: 70 terms of the next-70 list (asphalt, concrete and both), placed under their chosen parents | e.g. `flexible-pavement.html`, `superpave.html`, `asphalt-binder.html`, `tack-coat.html`, `joint.html` |
| Pages added 2026-10-28: 97 terms of the next-100 list, placed under their chosen parents (Blowup and Edge Deterioration, which the publications mention only in passing, are left out) | e.g. `service-life.html`, `pavement-management.html`, `continuously-reinforced-concrete-pavement.html` |
| Pub 408/2026 (Change No. 1) in place of Pub 408/2020 on every page, 2026-10-29 (the Pub 242 answers are unchanged); Wheel Path added under Distress | any page's References, `wheel-path.html` |
| Formula cards (rendered formula, symbols, source check) | 53 blocks of 16 formulas on 35 pages (2026-10-30). Before the 70 pages were added, these were the formulas and some of their pages: M_r = 1500 CBR (`california-bearing-ratio.html`, `modulus-of-subgrade-reaction-k-value.html`, `pavement-design.html`, `pavement-reconstruction.html`, `resilient-modulus.html`, `rigid-pavement-design.html`, `subgrade.html`, `undercutting.html`), concrete elastic modulus (`aashto-1993-design-guide.html`, `class-aa-concrete.html`, `elastic-modulus.html`, `portland-cement-concrete.html`, `rigid-pavement-design.html`), compaction percentage from Pub 408 (`base-course.html`, `base-repair.html`, `construction-joint.html`, `pavement-design.html`, `roller-compacted-concrete.html`), modulus of rupture (`class-aa-concrete.html`, `modulus-of-rupture.html`, `pavement-design.html`, `portland-cement-concrete.html`, `rigid-pavement-design.html`), Asphalt Adjustment Multiplier (`alternate-pavement-type-bidding.html`, `pavement-design-submission.html`, `pavement-type-selection.html`, `resurfacing.html`), AASHTO Group Index (`pavement-reconstruction.html`, `subgrade-evaluation.html`), lot payment from Pub 408 (`air-content.html`, `pavement-core.html`), coefficients of uniformity and curvature (`gradation.html`) |
| Distress pages re-reviewed 2026-10-28 (a question set for distresses: description, where it occurs, causes, severity, measurement, effects, repairs, prevention, specification limits) | `distress.html`, `cracking.html`, `spalling.html`, `corner-break.html`, `depression-settlement.html`, `pumping.html`, `void-loss-of-support.html`, `longitudinal-crack.html`, `transverse-crack.html`, `frost-heave.html` |
| Calculators for those formulas | `_apps/` (16) |
| Known issues (2026-10-30 build) | `stripping.html` shows 3 stray full-width `【` citation markers; `air-voids.html` shows one citation in doubled brackets; the figure step was rerun for all pages, so 8 existing pages have one source figure fewer (7 of them now none) and 6 have one more |

## How this repo is produced

Generated; do not hand-edit the HTML. It is a copy of stage 13 (html) of the llm-wiki-ui run
`pub-specs`, `21-concept-hierarchy-reorg-visual-tabular-fig-ada-formulas-html`, without the
`.complete` marker. The 2026-10-30 build comes from the rebuild run `pub-specs-m70` (the 244-page
merge, not yet moved into `pub-specs`). `.nojekyll` keeps GitHub Pages from dropping `_apps/`.

## Sources

The publication extractions behind these pages are **not republished here**. References link to
the publications on pa.gov.

Draft status: nothing here substitutes for the governing PennDOT publication.
