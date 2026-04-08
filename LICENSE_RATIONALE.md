# License Rationale

This repository is licensed under **CC BY-NC-ND 4.0** (Attribution — NonCommercial — NoDerivatives 4.0 International).

## Why this license

The goal is maximum control over how this curated list is reused, while still allowing standard GitHub collaboration.

### What each clause does

- **BY (Attribution)** — anyone reusing must credit Valeriy Manokhin and link to the source. This is the baseline requirement that also feeds the repo's citation-tracking system.
- **NC (NonCommercial)** — no commercial reuse without permission. Blocks paid courses, commercial blog posts, consulting deliverables, and books from quoting or republishing the curation without explicit licensing.
- **ND (NoDerivatives)** — no modified versions may be republished outside GitHub. Blocks translations, annotated remixes, reorderings, and "based on" adaptations from being distributed elsewhere.

### Why NC-ND and not something more permissive

1. **The list is a marketing and authority asset, not open infrastructure.** Its strategic purpose is to establish Valeriy Manokhin as the definitive curator of conformal prediction resources and drive traffic to the author's book and course. Allowing unrestricted commercial or derivative reuse would dilute that positioning.
2. **The commercial products (book, course) are the monetization layer.** The list itself should not be freely repackaged into competing commercial offerings.
3. **Translations and remixes are not wanted.** The canonical version of this list should remain the one maintained here. Off-GitHub forks with added commentary, condensed "cheat sheets," or reordered reading lists are explicitly not desired.
4. **NC-ND does not break GitHub forks or PRs.** GitHub's Terms of Service (Section D.5) grant every GitHub user an irrevocable right to view, fork, and clone public repositories regardless of the attached license. ND only blocks republishing modified versions *outside* GitHub. Standard fork-and-PR collaboration continues to work normally.

### Alternatives considered and rejected

- **CC0 1.0** — public domain. Would enable awesome.re badge compliance but provides zero control. Rejected: loses both attribution and commercial protection.
- **CC BY 4.0** — attribution only, permits commercial reuse and derivatives. Rejected: allows paid courses and commercial adaptations of the curation.
- **CC BY-NC 4.0** — blocks commercial reuse but allows non-commercial derivatives. Rejected: translations and annotated remixes are not desired even non-commercially.
- **CC BY-NC-SA 4.0** — adds copyleft share-alike to NC. Rejected: since derivatives are not allowed at all under ND, the share-alike clause is moot.
- **MIT / Apache / GPL** — software licenses, not designed for curated content. Rejected as a category.
- **Proprietary "All rights reserved"** — confuses users and GitHub ToS still grants fork rights. Rejected.

### Trade-offs accepted

- **Awesome-list badge non-compliance.** The official awesome.re manifesto requires CC0. The Awesome badge on the README is therefore technically misaligned with the license. This is acceptable because awesome.re inclusion is not a strategic priority.
- **Some commercial quoters will skip citing rather than email for permission.** This slightly reduces the input signal for the citation-tracking engine, but the trade-off is worth the commercial protection.
- **No translations.** Non-English audiences cannot legally create translated versions. Accepted.

### Related files

- `LICENSE` — full CC BY-NC-ND 4.0 text.
- `CITATION.cff` — declares `license: CC-BY-NC-ND-4.0` (SPDX identifier) and is consumed by GitHub's "Cite this repository" button.
