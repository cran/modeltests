
<!-- README.md is generated from README.Rmd. Please edit that file -->
modeltests
==========

[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/alexpghayes/modeltests?branch=master&svg=true)](https://ci.appveyor.com/project/alexpghayes/modeltests) [![Travis build status](https://travis-ci.org/alexpghayes/modeltests.svg?branch=master)](https://travis-ci.org/alexpghayes/modeltests) [![Coverage status](https://codecov.io/gh/alexpghayes/modeltests/branch/master/graph/badge.svg)](https://codecov.io/github/alexpghayes/modeltests?branch=master) [![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

`modeltests` is a package that exports tests for use in other packages. Currently I'm experimenting with moving the core broom tests into `modeltests`. This will allow other developers to guarantee that their tidier implementations that meet the broom `tidy()`, `glance()` and `augment()` specifications.

Example use:

-   The [`dustpan`](https://github.com/alexpghayes/dustpan) package is a small demonstration of how to use `modeltests` and `modelgenerics`
-   See the test suite in [`broom`](https://github.com/tidymodels/broom)

A detailed vignette is in progress in broom as well.
