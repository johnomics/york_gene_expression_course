---
title: York Gene Expression Course
---

This repository contains R Markdown documents and associated files for the differential expression sections of the University of York's Gene Expression Technologies course, first delivered in March 2019 by the [Genomics and Bioinformatics Lab](https://www.york.ac.uk/biology/technology-facility/genomics/).

The full course is three days long and includes material on RNA handling, qPCRs, RNA-seq library prep, alignment and pseudoalignment, and functional enrichment analysis in addition to the material here. The files in this repository cover about one day of material and could perhaps be run as a single day on differential expression.

The Day 1 material introduces some concepts common to qPCR and RNA-seq. Day 2 is a Sleuth tutorial, covering installation of R, RStudio, Sleuth, and running Sleuth on one data set. The Day 3 material explains how Sleuth works and how to design and interpret an RNA-seq experiment.

This repository contains small files but not the data sets themselves, which are available in [this Google Drive folder](https://drive.google.com/open?id=1GtgZ967s1BOm-DpXPG_XXfsNqxZpbZDN). The course is mostly based on the yeast data from [Gierlinski et al. 2015](https://academic.oup.com/bioinformatics/article/31/22/3625/240923) and [Schurch et al. 2016](https://rnajournal.cshlp.org/content/22/6/839.long).

The course may be available at [http://shiny.york.ac.uk/bioltf/gene_expression_course/day1/](http://shiny.york.ac.uk/bioltf/gene_expression_course/day1/).

To run the course locally yourself, open the Rmd files in [RStudio](https://www.rstudio.com) and Run Document on each day. You will need to install the `tidyverse`, `shiny`, `DT`, `learnr`, `MASS` and `sleuth` packages.

Please contact [John Davey](mailto:john.davey@york.ac.uk) with any queries.