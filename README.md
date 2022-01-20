# NIST Open-Source Software Repository Template

This is the recommended template for NIST employees to use for new
open-source software repositories. To use it, please click on the
green "Use this template" button at the top of the [page][gh-rep].

## Requirements to post public repositories to [usnistgov][gh-nst]

Use of this resource by NIST employees is subject to the
[Rules of Behavior for GitHub (PDF)][gh-rob]. For details, please
consult the Office of Data & Informatics'
[Quickstart Guide to GitHub at NIST][gh-odi].

### README

Each repository will contain a [README][wk-rdm] file, preferably
formatted using GitHub-flavored [Markdown][gh-mdn] and named
`README.md`. This file must contain:

1. Software or Data description
   - Statements of purpose and maturity
   - Technical installation instructions
1. Contact information
   - PI name, NIST OU, Division, and Group names
   - Contact email address at NIST
   - Details of mailing lists, chatrooms, and discussion forums,
     where applicable
1. Related Material
   - URL for associated project on <nist.gov> or other Department of
     Commerce site, if available
   - References to user guides if stored outside of GitHub
1. Directions on appropriate citation with example text
1. References to any included non-public domain software modules, and
   additional license language if needed, *e.g.* [BSD][li-bsd],
   [GPL][li-gpl], or [MIT][li-mit]

### Terms of Use: `LICENSE.md`

Each repository will contain a file named `LICENSE.md` that is
phrased in compliance with the Public Access to NIST Research
[*Copyright, Fair Use, and Licensing Statement for SRD, Data, and
Software*][nist-open].

- You may use the version of [LICENSE.md](LICENSE.md) included in
  this repository
- When in doubt, copy and include the contents of the relevant
  statement inside a "blue box" in its entirety
- *After* the NIST disclaimer of copyright and warranty, include
  copyright and licensing statements of any third-party software that
  are legally bundled with the code in compliance with the conditions
  of those licenses
  - *Note:* There is [ongoing discussion](gh-tpl) on the best way to
    handle attribution and license inclusion for third-party
    dependencies: please weigh in!

### CODEOWNERS

This template repository includes a file named [CODEOWNERS](CODEOWNERS),
which visitors can view to discover which GitHub users are "in charge"
of the repository.
More crucially, GitHub uses it to assign reviewers on pull requests.
GitHub documents the file (and how to write one) [here][gh-cdo].

***Please update this file*** to point to your own account or team,
so that the [Open-Source Team][gh-ost] doesn't get spammed with
spurious review requests. *Thanks!*

### Repository Metadata: `CODEMETA.yaml`

This repository includes a file named `CODEMETA.yaml`, used by the NIST
Software Portal to sort your work under the appropriate thematic
homepage. ***Please update this file*** with the appropriate "theme" and
"category" for your code/data/software. The Tier 1 themes are:

- [Advanced communications](https://www.nist.gov/advanced-communications)
- [Bioscience](https://www.nist.gov/bioscience)
- [Buildings and Construction](https://www.nist.gov/buildings-construction)
- [Chemistry](https://www.nist.gov/chemistry)
- [Electronics](https://www.nist.gov/electronics)
- [Energy](https://www.nist.gov/energy)
- [Environment](https://www.nist.gov/environment)
- [Fire](https://www.nist.gov/fire)
- [Forensic Science](https://www.nist.gov/forensic-science)
- [Health](https://www.nist.gov/health)
- [Information Technology](https://www.nist.gov/information-technology)
- [Infrastructure](https://www.nist.gov/infrastructure)
- [Manufacturing](https://www.nist.gov/manufacturing)
- [Materials](https://www.nist.gov/materials)
- [Mathematics and Statistics](https://www.nist.gov/mathematics-statistics)
- [Metrology](https://www.nist.gov/metrology)
- [Nanotechnology](https://www.nist.gov/nanotechnology)
- [Neutron research](https://www.nist.gov/neutron-research)
- [Performance excellence](https://www.nist.gov/performance-excellence)
- [Physics](https://www.nist.gov/physics)
- [Public safety](https://www.nist.gov/public-safety)
- [Resilience](https://www.nist.gov/resilience)
- [Standards](https://www.nist.gov/standards)
- [Transportation](https://www.nist.gov/transportation)

### FAIR Software & Data

Some advice and links for producing FAIR software and data can be
found in [`fair-software.md`](fair-software.md).

<!-- References -->

[gh-cdo]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
[gh-mdn]: https://github.github.com/gfm/
[gh-nst]: https://github.com/usnistgov
[gh-odi]: https://odiwiki.nist.gov/ODI/GitHub.html
[gh-ost]: https://github.com/orgs/usnistgov/teams/opensource-team
[gh-rob]: https://odiwiki.nist.gov/pub/ODI/GitHub/GHROB.pdf
[gh-rep]: https://github.com/usnistgov/opensource-repo/
[gh-tpl]: https://github.com/usnistgov/carpentries-development/discussions/3
[li-bsd]: https://opensource.org/licenses/bsd-license
[li-gpl]: https://opensource.org/licenses/gpl-license
[li-mit]: https://opensource.org/licenses/mit-license
[nist-open]: https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications
[wk-rdm]: https://en.wikipedia.org/wiki/README
