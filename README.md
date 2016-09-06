# rmarkdown-css
Some custom css for RMarkdown's HTML output

RMarkdown header settings

``` r
---
title: "Blah blah"
output:
  html_document:
    css: style.css
    code_folding: hide
    dev: CairoSVG
    fig_height: 10
    fig_width: 15
    toc: yes
    toc_float:
      collapsed: false
---
```
