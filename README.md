# cnrt-specs-wiki-stage

Staging build of the PennDOT **specifications** wiki: concept pages synthesized from PennDOT
Publication 242, Pavement Policy Manual (May 2015 Edition, Change No. 10), and Publication
408/2020 Specifications (Change No. 11).

Live: https://ig0r.github.io/cnrt-specs-wiki-stage/

| What | Where |
|---|---|
| Concept hierarchy (27 pages, root `penndot-pavement-policy-manual.html`) | `index.html` |
| Formula cards (rendered formula, symbols, source check) | `pavement-design.html`, `subgrade.html`, `pavement-structure.html` (M_r = 1500 CBR), `resurfacing.html` (Asphalt Adjustment Multiplier), `base-course.html` (RCC compaction percentage, Pub 408) |
| Calculators for those formulas | `_apps/` |

## How this repo is produced

Generated; do not hand-edit the HTML. It is a copy of stage 13 (html) of the llm-wiki-ui run
`pub-specs`, `21-concept-hierarchy-reorg-visual-tabular-fig-ada-formulas-html`, without the
`.complete` marker. `.nojekyll` keeps GitHub Pages from dropping `_apps/`.

## Sources

The publication extractions behind these pages are **not republished here**. References link to
the publications on pa.gov.

Draft status: nothing here substitutes for the governing PennDOT publication.
