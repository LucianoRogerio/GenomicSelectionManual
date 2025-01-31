---
title: "Genomic Prediction and Selection Manual"
author: "Marnin Wolfe"
date: "2022-03-15"
site: bookdown::bookdown_site
documentclass: book
bibliography: [refs.bib, book.bib, packages.bib]
url: https://wolfemd.github.io/GenomicSelectionManual
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  Training resources and examples of standard procedures for 
  genomic selection-related computation.
biblio-style: apalike
csl: genetics.csl
github-repo: wolfemd/GenomicSelectionManual
---

# Preamble

This manual aims at providing a training on the implementation of genomics-enabled decision support for [NextGen Cassava Breeding Project](http://www.nextgencassava.org) and its community of practice partnerships.

Associated with this manual we will provide a codebase and standard operating procedures for a reproducible BreedBase-integrated workflow.

Two major sections are currently planned:

1.  **Genomic (Mate) Selection Workflow Example:** Using an example dataset from [Cassavabase](https://www.cassavabase.org/), work hands-on, with demos, over the full workflow. Provide skeleton for each pipeline segment: purpose, SOP, checklist, template, necessary inputs, KPI and outputs.

2.  **Data wrangling and reproducibility:** Intro and hands-on with the computing and data environment / manipulation side of things. Learning resources/links. No excel! R, Tidyverse, functions, loops, bash / command line, genomic data manipulation programs.

Collectively these two components will support learning **Genomic prediction and selection: in practice**.

**Genomic prediction and selection: in theory**

Students also may further need/want to learn the statistical and quantitative genetic theory. An additional section is planned that, at a minimum will provide guidance and access to reading and other learning resources. For starters, [@falconer2003introduction; @isik2017genetic; @bernardo2020breeding; @lynch1998genetics]!

# Overview Process Map

I created several "process maps" at varying levels of detail, to diagrammatically outline the orders of operations for genomic selection. Below is high-level overview process map:

![](images/OverviewProcessMap.png){width=100%}


