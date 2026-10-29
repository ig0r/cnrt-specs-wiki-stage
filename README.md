# cnrt-specs-wiki-stage

Staging build of the PennDOT **specifications** wiki: concept pages synthesized from PennDOT
Publication 242, Pavement Policy Manual (May 2015 Edition, Change No. 10), and Publication
408/2020 Specifications (Change No. 11).

Live: https://ig0r.github.io/cnrt-specs-wiki-stage/

| What | Where |
|---|---|
| Concept hierarchy (174 pages, root `penndot-pavement-policy-manual.html`, five top-level topics) | `index.html` |
| Pages added 2026-10-28: 97 terms of the next-100 list, placed under their chosen parents (3 terms the publications mention only in passing are left out) | e.g. `service-life.html`, `pavement-management.html`, `continuously-reinforced-concrete-pavement.html` |
| Formula cards (rendered formula, symbols, source check) | 27 blocks of 8 formulas on 21 pages: M_r = 1500 CBR (`california-bearing-ratio.html`, `modulus-of-subgrade-reaction-k-value.html`, `pavement-design.html`, `pavement-reconstruction.html`, `resilient-modulus.html`, `rigid-pavement-design.html`, `subgrade.html`), concrete elastic modulus (`aashto-1993-design-guide.html`, `class-aa-concrete.html`, `elastic-modulus.html`, `portland-cement-concrete.html`, `rigid-pavement-design.html`), Asphalt Adjustment Multiplier (`alternate-pavement-type-bidding.html`, `pavement-design-submission.html`, `pavement-type-selection.html`, `resurfacing.html`), modulus of rupture (`class-aa-concrete.html`, `modulus-of-rupture.html`, `portland-cement-concrete.html`, `rigid-pavement-design.html`), AASHTO Group Index (`compaction.html`, `pavement-reconstruction.html`, `subgrade-evaluation.html`), compaction percentage from Pub 408 (`base-course.html`, `roller-compacted-concrete.html`), coefficients of uniformity and curvature (`gradation.html`) |
| Distress pages re-reviewed 2026-10-28 (a question set for distresses: description, where it occurs, causes, severity, measurement, effects, repairs, prevention, specification limits) | `distress.html`, `cracking.html`, `spalling.html`, `corner-break.html`, `depression-settlement.html`, `pumping.html`, `void-loss-of-support.html`, `longitudinal-crack.html`, `transverse-crack.html`, `frost-heave.html` |
| Calculators for those formulas | `_apps/` (8) |

## How this repo is produced

Generated; do not hand-edit the HTML. It is a copy of stage 13 (html) of the llm-wiki-ui run
`pub-specs`, `21-concept-hierarchy-reorg-visual-tabular-fig-ada-formulas-html`, without the
`.complete` marker. `.nojekyll` keeps GitHub Pages from dropping `_apps/`.

## Sources

The publication extractions behind these pages are **not republished here**. References link to
the publications on pa.gov.

Draft status: nothing here substitutes for the governing PennDOT publication.
