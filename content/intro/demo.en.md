---
title: Demo
weight: 1
output: hugodown::md_document
rmd_hash: 80bc6c955c11e210

---

System setup
------------

-   [`install.packages("devtools")`](https://rdrr.io/r/utils/install.packages.html). [Setup chapter of the R packages book](https://r-pkgs.org/setup.html).

-   usethis and devtools setup in my .Rprofile. [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html)

Package creation
----------------

-   [`usethis::create_package("/home/maelle/Documents/teaching/minipkg")`](https://usethis.r-lib.org/reference/create_package.html)

-   [`usethis::use_git()`](https://usethis.r-lib.org/reference/use_git.html)

-   in a shell `git branch -m master main`

-   [`usethis::use_r("current-time")`](https://usethis.r-lib.org/reference/use_r.html)

-   `devtools::load()`, `what_time()`

-   Insert roxygen2 skeleton.

-   [`devtools::document()`](https://devtools.r-lib.org//reference/document.html), `?what_time`

-   [`devtools::check()`](https://devtools.r-lib.org//reference/check.html), [`usethis::use_mit_license`](https://usethis.r-lib.org/reference/licenses.html)

-   add an argument, `@param language blabla` in docs, [`devtools::document()`](https://devtools.r-lib.org//reference/document.html), `?what_time`

-   [`usethis::use_test("current-time")`](https://usethis.r-lib.org/reference/use_r.html)

-   [`devtools::test()`](https://devtools.r-lib.org//reference/test.html)

-   `use_package("praise")`

-   [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), write stuff

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html)

-   [`install.packages("pkgdown")`](https://rdrr.io/r/utils/install.packages.html), GitHub actions

