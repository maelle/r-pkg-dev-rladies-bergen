---
title: Demo
weight: 1
output: hugodown::md_document
rmd_hash: 2395edbdaa271e9e

---

System setup
------------

-   [`install.packages("devtools")`](https://rdrr.io/r/utils/install.packages.html). [Setup chapter of the R packages book](https://r-pkgs.org/setup.html).

-   usethis and devtools setup in my .Rprofile. [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html)

Package creation
----------------

-   [`available::available("minipkg")`](https://rdrr.io/pkg/available/man/available.html)

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

-   [`devtools::check()`](https://devtools.r-lib.org//reference/check.html)

-   modify function, `use_package("praise")`

-   [`devtools::check()`](https://devtools.r-lib.org//reference/check.html)

-   [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), write stuff

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html), [`usethis::use_github_links()`](https://usethis.r-lib.org/reference/use_github_links.html)

-   [`usethis::use_github_action_check_standard()`](https://usethis.r-lib.org/reference/use_github_action.html)

-   [`install.packages("pkgdown")`](https://rdrr.io/r/utils/install.packages.html), [`usethis::use_pkgdown()`](https://usethis.r-lib.org/reference/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html)

-   [`usethis::use_github_action("pkgdown")`](https://usethis.r-lib.org/reference/use_github_action.html), change GitHub pages settings of the repo, add URL to pkgdown config and to DESCRIPTION.

