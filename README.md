[![Website](https://img.shields.io/badge/sitcomtn--179-lsst.io-brightgreen.svg)](https://sitcomtn-179.lsst.io)
[![CI](https://github.com/lsst-sitcom/sitcomtn-179/actions/workflows/ci.yaml/badge.svg)](https://github.com/lsst-sitcom/sitcomtn-179/actions/workflows/ci.yaml)

# Characterizing the Influence of Wind Speed and Direction on Portable and Fixed DIMM seeing measurements

## SITCOMTN-179

This technical note provides a comprehensive comparative analysis of seeing measurements obtained from portable and fixed Differential Image Motion Monitors (DIMM). We investigate the correlation between these two systems and quantify the systematic influences of local meteorological conditions. Specifically, we demonstrate the dependency of seeing discrepancies on wind speed.

**Links:**

- Publication URL: https://sitcomtn-179.lsst.io
- Alternative editions: https://sitcomtn-179.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-179
- Build system: https://github.com/lsst-sitcom/sitcomtn-179/actions/


## Build this technical note

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

```sh
git clone https://github.com/lsst-sitcom/sitcomtn-179
cd sitcomtn-179
make init
make html
```

Repeat the `make html` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run `make clean`.

The built technote is located at `_build/html/index.html`.

## Publishing changes to the web

This technote is published to https://sitcomtn-179.lsst.io whenever you push changes to the `main` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-179.lsst.io/v.

## Editing this technical note

The main content of this technote is in `index.md` (a Markdown file parsed as [CommonMark/MyST](https://myst-parser.readthedocs.io/en/latest/index.html)).
Metadata and configuration is in the `technote.toml` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
