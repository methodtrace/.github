![methodtrace](https://raw.githubusercontent.com/methodtrace/.github/main/assets/methodtrace-lockup.svg)

Reproduction and verification artifacts for published and preprinted research papers.

Each repository here corresponds to one paper and holds what is needed to check that paper's results independently: source, configuration and reproduction instructions, plus, depending on the paper, fixed seeds and generated records (simulation studies), exact certificates and a verifier (mathematical results), or, for papers without executable code, the datasets, protocols and extraction tables behind the reported results. Repositories are frozen at a release tag matching the paper revision they support, and each tagged release is archived with a version DOI.

Papers span applied work on streaming and connected-TV advertising systems and measurement, and mathematical work in combinatorial optimization. Authors vary by paper.

## Repositories

| Repository | Paper | Field | Record | Release |
| --- | --- | --- | --- | --- |
| [2026-dai-timing](https://github.com/methodtrace/2026-dai-timing) | Trigger Timing, Deadline Readiness, and Event-Aligned Accounting for Dynamic Ad Insertion | Multimedia systems | [arXiv:2609.19899](https://arxiv.org/abs/2609.19899) | `1.0.0` · [doi.org/10.5281/zenodo.22774143](https://doi.org/10.5281/zenodo.22774143) |
| [2026-inverse-knapsack-hull-pairs](https://github.com/methodtrace/2026-inverse-knapsack-hull-pairs) | Inverse knapsack at two capacities: which pairs of value–cardinality hulls are realisable? | Combinatorial optimization | forthcoming | unreleased |

## Conventions

**Naming.** `<year>-<short-slug>`, one repository per paper, no version numbers in repository names.

**Records.** The Record column lists persistent identifiers only: an arXiv identifier or a DOI. Once a paper has a version of record, its DOI is listed first and the preprint identifier is kept beside it. Venues are not named before acceptance.

**Releases.** The Release column gives the current tag and the version DOI of its archived copy. A repository with no archived release is marked unreleased. A tag is immutable once archived. Corrections appear as a new tag and a new version DOI; earlier releases are never rewritten or deleted.

**Cross-linking.** The archive is deposited before the paper is posted, so that the paper can cite the archive DOI. Once the paper has its own identifier, that identifier is added to the archive record as a related identifier ("is supplement to"), and the same is done for the version of record on publication. Manuscripts are not deposited in the archive. Each release's notes state the manuscript revision number and date the release supports, so a reader can confirm the pairing even where the preprint server shows only the latest revision.

**Licensing.** Executable code is under Apache-2.0. Data, tables, fixtures, certificates and specification templates are under CC BY 4.0. Each repository carries whichever of `LICENSE` (code) and `LICENSE-DATA` (data) apply. Article and supplement text is not covered by either and remains under its publisher's terms.

**Citation.** Cite the paper, not the repository, unless you are specifically referring to the code or data. Every repository carries a `CITATION.cff` with the paper reference and the archive DOI.

**Reproduction.** Each repository's README gives platform and environment requirements, setup and run steps, and the expected output, so a result can be checked without contacting the authors. Where a repository has no executable code, the README instead describes each file, its provenance, and how it maps to the paper's tables and figures.

## Scope

These repositories are research artifacts, not maintained software. They are not libraries, they take no feature requests, and they are not intended for production use. Issues reporting a reproduction failure, a certificate that fails verification, or a defect in a published result are welcome and will be addressed; a fix that changes a reported result is published as a corrected release with its own DOI, alongside the original.
