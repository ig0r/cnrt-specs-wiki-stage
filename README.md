# cnrt-specs-wiki-stage

Staging build of the PennDOT **specifications** wiki: concept pages synthesized from PennDOT
Publication 242, Pavement Policy Manual (May 2015 Edition, Change No. 10), and Publication
408/2020 Specifications (Change No. 11).

Live: https://ig0r.github.io/cnrt-specs-wiki-stage/

| What | Where |
|---|---|
| Concept hierarchy (77 pages, root `penndot-pavement-policy-manual.html`) | `index.html` |
| Formula cards (rendered formula, symbols, source check) | 14 blocks of 8 formulas on 10 pages: M_r = 1500 CBR (`pavement-design.html`, `rigid-pavement-design.html`, `pavement-reconstruction.html`, `subgrade.html`), Asphalt Adjustment Multiplier (`resurfacing.html`, `pavement-type-selection.html`), AASHTO Group Index (`compaction.html`, `pavement-reconstruction.html`), coefficients of uniformity and curvature (`gradation.html`), concrete elastic modulus and modulus of rupture (`rigid-pavement-design.html`), compaction percentage from Pub 408 (`base-course.html`, `roller-compacted-concrete.html`) |
| Calculators for those formulas | `_apps/` (8) |

## How this repo is produced

Generated; do not hand-edit the HTML. It is a copy of stage 13 (html) of the llm-wiki-ui run
`pub-specs`, `21-concept-hierarchy-reorg-visual-tabular-fig-ada-formulas-html`, without the
`.complete` marker. `.nojekyll` keeps GitHub Pages from dropping `_apps/`.

## Sources

The publication extractions behind these pages are **not republished here**. References link to
the publications on pa.gov.

Draft status: nothing here substitutes for the governing PennDOT publication.
