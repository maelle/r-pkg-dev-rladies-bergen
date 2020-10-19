---
title: Snippets
weight: 1
hidden: true
chapter: false
disableToc: false
---

For copy-pasting during demos.

```r
what_time <- function() {
  time <- format(Sys.time(), "%H:%M")
  sprintf("It is %s now!", time)
}
```