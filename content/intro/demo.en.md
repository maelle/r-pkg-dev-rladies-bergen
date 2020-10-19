---
title: Demo
weight: 1
output: hugodown::md_document
rmd_hash: 9ffc1aa49734e09b

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

