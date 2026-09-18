<img src="https://raw.githubusercontent.com/methodtrace/.github/main/assets/methodtrace-lockup.svg" alt="methodtrace" width="420">

Reproduction artifacts for published and preprinted research papers.

Each repository here corresponds to one paper. A repository holds the source, configuration, fixed seeds, generated records, verification fixtures and reproduction instructions needed to re-derive that paper's reported quantities from scratch. Repositories are frozen at a release tag matching the paper revision they support, and each tagged release is archived with a version DOI.

Work spans streaming and connected-TV advertising systems, measurement and accounting methods, and reviews of existing literature and public data. Authors vary by paper.

## Repositories

| Repository | Paper | Release | Archive |
|---|---|---|---|
| [2026-dai-timing](https://github.com/methodtrace/2026-dai-timing) | Trigger Timing, Deadline Readiness, and Event-Aligned Accounting for Dynamic Ad Insertion | `1.0.0` | DOI pending release |
| [2026-inverse-knapsack-hull-pairs](https://github.com/methodtrace/2026-inverse-knapsack-hull-pairs) | Inverse knapsack at two capacities: which pairs of value–cardinality
hulls are realisable? | `1.0.0` | DOI pending release |

## Conventions

**Naming.** `<year>-<short-slug>`, one repository per paper, no version numbers in repository names.

**Releases.** A tag is immutable once archived. Corrections appear as a new tag and a new version DOI; earlier releases are never rewritten or deleted.

**Licensing.** Executable code is under Apache-2.0. Data, tables, fixtures and specification templates are under CC BY 4.0. Each repository states its scopes in `LICENSE` and `LICENSE-DATA`. Article and supplement text is not covered by either and remains under its publisher's terms.

**Citation.** Cite the paper, not the repository, unless you are specifically referring to the code or data. Every repository carries a `CITATION.cff` with the paper reference and the archive DOI.

**Reproduction.** Each repository's README gives platform and environment requirements, setup and run steps, and the expected output, so a result can be checked without contacting the authors.

## Scope

These repositories are research artifacts, not maintained software. They are not libraries, they take no feature requests, and they are not intended for production use. Issues reporting a reproduction failure or a defect in a published result are welcome and will be addressed; a fix that changes a reported quantity is published as a corrected release with its own DOI, alongside the original.
