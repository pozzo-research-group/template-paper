# paper-short-name

<!-- After "Use this template", work through this checklist, then delete it.
- [ ] Rename the repository (lowercase kebab-case) and set its description and the `project` topic
      (change to `paper` when published).
- [ ] LICENSE: replace YEAR and AUTHOR NAMES. MIT is the group default for new repositories.
- [ ] CITATION.cff: software authors (with ORCIDs) and, once published, the paper. Run `cffconvert --validate`.
- [ ] environment.yml: pin the exact versions you used.
- [ ] Deposit data on Zenodo and fill in data/README.md.
- [ ] At submission: ask Lilo to enable Zenodo, release v1.0.0, and put the version DOI in the paper.
See the group's repository guide: https://github.com/pozzo-research-group/.github/blob/main/REPOSITORY_GUIDE.md
-->

<!-- After the first Zenodo release, add the concept-DOI badge:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.NNNNNNN.svg)](https://doi.org/10.5281/zenodo.NNNNNNN) -->

Code that reproduces the results in:

> Authors. *Paper title.* Journal, year. [doi:10.xxxx/xxxxx](https://doi.org/10.xxxx/xxxxx)

## Install

```
conda env create -f environment.yml
conda activate paper-short-name
```

## Reproduce the figures

| Figure | Script or notebook | Output |
|---|---|---|
| Fig. 1 | `scripts/fig1.py` | `figures/fig1.png` |
| Fig. 2 | `notebooks/fig2.ipynb` | `figures/fig2.png` |

Run the steps in order. Each one reads data from `data/` (see [data/README.md](data/README.md)).

## Data

See [data/README.md](data/README.md).

## Maintainer

Name (GitHub @username). Report problems in [Issues](../../issues).

## How to cite

Please cite the paper above. To cite the code itself, see [CITATION.cff](CITATION.cff) or
**"Cite this repository"** on the GitHub page.

## License

[MIT](LICENSE)
