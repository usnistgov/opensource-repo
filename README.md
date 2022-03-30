# NIST Open-Source Software Repository Template

<!-- Text within tags like these are comments, and will not
     appear online. Feel free to delete them from your copy. -->

## Description

<!-- Required. Please replace the text in this section with a
      summary of the work this repository represents, or intends
      to. Sub-sections describing file contents can/should be
      removed, or replaced with a file format or folder hierarchy
      description. -->

Use of GitHub by NIST employees for government work is subject to
the [Rules of Behavior for GitHub][gh-rob]. This is the
recommended template for NIST employees, since it contains
required files with approved text. For details, please consult
the Office of Data & Informatics' [Quickstart Guide to GitHub at
NIST][gh-odi].

Please click on the green **Use this template** button above to
create a new repository under the [usnistgov][gh-nst]
organization for your own open-source work. Please do not "fork"
the repository directly, and do not create the templated
repository under your individual account.

The key files contained in this repository -- which will also
appear in templated copies -- are listed below, with some things
to know about each.

> ### README
>
> Each repository will contain a [README file][wk-rdm], preferably
> formatted using [GitHub-flavored Markdown][gh-mdn] and named
> `README.md` (this file). It must contain:
>
> 1. Software or Data description
>    - Statements of purpose and maturity
>    - Technical installation instructions
> 1. Contact information
>    - PI name, NIST OU, Division, and Group names
>    - Contact email address at NIST
>    - Details of mailing lists, chatrooms, and discussion forums,
>      where applicable
> 1. Related Material
>    - URL for associated project on <nist.gov> or other Department
>      of Commerce site, if available
>    - References to user guides if stored outside of GitHub
> 1. Directions on appropriate citation with example text
> 1. References to any included non-public domain software modules,
>    and additional license language if needed, *e.g.* [BSD][li-bsd],
>    [GPL][li-gpl], or [MIT][li-mit]
>
> The more detailed your README, the more likely our colleagues around
> the world are to find it through a Web search.
>
> - Cornell University's Research Data Management Service Group has a
>   very good [*Guide to Writing README-style Metadata*][cornell-meta]
>   which can help you prepare descriptive top-level documentation
>   (i.e., this README).
> - [NIST Suborder 1801.02][nist-s-1801-02] includes guidance for
>   documenting published datasets. The Suborder states that the
>   following items should be included if appropriate to your data
>   (or source code):
>
>   - a description of the data (code)
>   - a description of data tables (code listings)
>   - a statement describing how to obtain the data (code)
>   - operating system requirements for building and running
>   - specification of applications programs required to access and
>     use any of the files associated with the data (code)
>   - statement of inputs required from the user
>   - statement concerning technical support available from NIST
>     with appropriate contact information
>   - [the disclaimer][nist-disclaimer] approved by the Office of
>     Chief Counsel for NIST or another suitable and approved
>     disclaimer.
>
> ### Terms of Use: `LICENSE.md`
>
> Each repository will contain a file named `LICENSE.md` that is
> phrased in compliance with the Public Access to NIST Research
> [*Copyright, Fair Use, and Licensing Statement for SRD, Data, and
> Software*][nist-open].
>
> - The version of [LICENSE.md](LICENSE.md) included in this
>   repository is approved for use.
> - When in doubt, copy and include the contents of the relevant
>   statement inside a "blue box" in its entirety
> - As subsections of [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md),
>   include copyright and licensing statements of any third-party
>   software that are legally bundled with the code in compliance with
>   the conditions of those licenses. If this does not apply, you may
>   delete that file.
>
> ### CODEOWNERS
>
> This template repository includes a file named
> [CODEOWNERS](CODEOWNERS), which visitors can view to discover
> which GitHub users are "in charge" of the repository. More
> crucially, GitHub uses it to assign reviewers on pull requests.
> GitHub documents the file (and how to write one) [here][gh-cdo].
>
> ***Please update this file*** to point to your own account or
> team, so that the [Open-Source Team][gh-ost] doesn't get spammed
> with spurious review requests. *Thanks!*
>
> ### Repository Metadata: `CODEMETA.yaml`
>
> This repository includes a file named `CODEMETA.yaml`, used by
> the NIST Software Portal to sort your work under the appropriate
> thematic homepage. ***Please update this file*** with the
> appropriate "theme" and "category" for your code/data/software.
> The Tier 1 themes are:
>
> - [Advanced communications](https://www.nist.gov/advanced-communications)
> - [Bioscience](https://www.nist.gov/bioscience)
> - [Buildings and Construction](https://www.nist.gov/buildings-construction)
> - [Chemistry](https://www.nist.gov/chemistry)
> - [Electronics](https://www.nist.gov/electronics)
> - [Energy](https://www.nist.gov/energy)
> - [Environment](https://www.nist.gov/environment)
> - [Fire](https://www.nist.gov/fire)
> - [Forensic Science](https://www.nist.gov/forensic-science)
> - [Health](https://www.nist.gov/health)
> - [Information Technology](https://www.nist.gov/information-technology)
> - [Infrastructure](https://www.nist.gov/infrastructure)
> - [Manufacturing](https://www.nist.gov/manufacturing)
> - [Materials](https://www.nist.gov/materials)
> - [Mathematics and Statistics](https://www.nist.gov/mathematics-statistics)
> - [Metrology](https://www.nist.gov/metrology)
> - [Nanotechnology](https://www.nist.gov/nanotechnology)
> - [Neutron research](https://www.nist.gov/neutron-research)
> - [Performance excellence](https://www.nist.gov/performance-excellence)
> - [Physics](https://www.nist.gov/physics)
> - [Public safety](https://www.nist.gov/public-safety)
> - [Resilience](https://www.nist.gov/resilience)
> - [Standards](https://www.nist.gov/standards)
> - [Transportation](https://www.nist.gov/transportation)

## Contact Information

<!-- Required section. Please list your project's developers
     instead of the opensource-repo team. Note that NIST
     employees are required to list their email address in their
     GitHub profile, so the general public can get in touch. -->

[usnistgov/opensource-repo][gh-osr] is developed and maintained
by the [opensource-team][gh-ost], principally:

- Gretchen Greene, @GRG2
- Yannick Congo, @faical-yannick-congo
- Trevor Keller, @tkphd

This information is also reflected in [CODEOWNERS](CODEOWNERS).

## Related Material

<!-- Please list any publications, websites, or work related to
     your project. -->

Some advice and links for producing FAIR software and data can be
found in [`fair-software.md`](fair-software.md).

## Cite This Work

<!-- Please provide a DOI, URL, and suggested citation. -->

While this template repository has not been published, you can
cite it as follows:

> F. Congo, G. Greene, T. Keller, and A. Morey. *NIST Open-Source
> Software Repository Template* [Source Code]. Online:
> <https://github.com/usnistgov/opensource-repo> (accessed 15
> March 2022).

Other software developed at NIST can be found in the [Open-Source
Software Repository][nist-code].

## Third-Party Dependencies

<!-- If your project includes source code from third parties, note
     those dependencies below and link to their sub-sections in
     [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md). If those
     terms of use prohibit you from including the third-party work
     directly, make note of how to obtain it, and make sure it is not
     checked in to this repository. -->

This repository does not include any third-party software: it is
only subject to the [NIST Disclaimer of Warranty](LICENSE.md).

<!-- References -->

[gh-cdo]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
[gh-mdn]: https://github.github.com/gfm/
[gh-nst]: https://github.com/usnistgov
[gh-odi]: https://odiwiki.nist.gov/ODI/GitHub.html
[gh-osr]: https://github.com/usnistgov/opensource-repo/
[gh-ost]: https://github.com/orgs/usnistgov/teams/opensource-team
[gh-rob]: https://odiwiki.nist.gov/pub/ODI/GitHub/GHROB.pdf
[gh-tpl]: https://github.com/usnistgov/carpentries-development/discussions/3
[li-bsd]: https://opensource.org/licenses/bsd-license
[li-gpl]: https://opensource.org/licenses/gpl-license
[li-mit]: https://opensource.org/licenses/mit-license
[nist-code]: https://code.nist.gov
[nist-disclaimer]: https://www.nist.gov/open/license
[nist-s1801-02]: https://inet.nist.gov/adlp/directives/review-data-intended-publication
[nist-open]: https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications
[wk-rdm]: https://en.wikipedia.org/wiki/README
