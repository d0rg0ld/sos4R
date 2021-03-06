
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sos4R - R client for OGC SOS

sos4R is an extension for the R environment for statistical computing
and visualization. It allows to query data from standard conform SOS
instances using simple R function calls and does no require any
knowledge about the Sensor Web. It is easily extendible for new data
models and opens the huge amount of analysis and visualization features
of the R environment for the Sensor Web.

[![cran
checks](https://cranchecks.info/badges/summary/sos4R)](https://cran.r-project.org/web/checks/check_results_sos4R.html)
[![Build
Status](https://travis-ci.org/52North/sos4R.png)](https://travis-ci.org/52North/sos4R)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/52North/sos4R?branch=master&svg=true)](https://ci.appveyor.com/project/52North/sos4R)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

## Documentation & Links

  - **Website**: <https://52north.github.io/sos4R>
  - CRAN: <https://CRAN.R-project.org/package=sos4R>
  - Source code: <https://github.com/52North/sos4R>
  - **Support**: [![Join the chat at
    https://gitter.im/52North/sos4R](https://badges.gitter.im/52North/sos4R.svg)](https://gitter.im/52North/sos4R)
  - **Developer documentation:**
    <https://52north.github.io/sos4R/DEV-README.html>
  - Ohloh: <https://www.ohloh.net/p/sos4R>

## Development

[![Build
Status](https://travis-ci.org/52North/sos4R.png?branch=dev)](https://travis-ci.org/52North/sos4R)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/52North/sos4R?branch=dev&svg=true)](https://ci.appveyor.com/project/52North/sos4R)

sos4R is developed on GitHub using the [fork & pull development
model](https://help.github.com/articles/using-pull-requests/#fork--pull).
The [main repository’s issue
tracker](https://github.com/52North/sos4R/issues) is used to coordinate
development.

The `master` branch represents the current version that is [published on
CRAN](https://CRAN.R-project.org/package=sos4R), the `dev` branch is the
current development version.

See file `DEV-README.md` for developer documentation.

### Install the development version

You can install the current development version (= the next release for
CRAN) directly from GitHub with the following commands.

``` r
install.packages("devtools")
devtools::install_github("52North/sos4R", ref = "dev")
# To also install the vignettes run: devtools::install_github("52North/sos4R", build_vignettes = TRUE)
```

### Contributors

  - [@nuest](https://github.com/nuest)
  - [@edzer](https://github.com/edzer)
  - [@BenGraeler](https://github.com/BenGraeler)
  - [@bpross-52n](https://github.com/bpross-52n)
  - [@EHJ-52n](https://github.com/EHJ-52n)

sos4R is a project of
[52°North](https://52north.org).

[![](https://52north.org/wp-content/uploads/2016/06/logo-main.png)](https://52north.org)

### Contact

Do you have a question that is not anwsered in the links above? Contact
Daniel: [daniel.nuest@uni-muenster.de](daniel.nuest@uni-muenster.de)

## License

This R extension package is licensed under [GPL
v2.0](https://tldrlegal.com/license/gnu-general-public-license-v2).

Documentation (e.g. vignette) is published under [CC
BY 4.0](http://creativecommons.org/licenses/by/4.0/).
