---
title: Metatranscriptome assembly for protistan communities
date: 2022-04-25T17:58:29.591Z
draft: false
featured: false
image:
  filename: eukrhythmic-fig1-paper.png
  focal_point: Smart
  preview_only: false
---
The field of omics has quickly exploded into one of the most popular routes of biological inference. And this is for good reason: omics studies are *powerful*, and, increasingly, they are fast and cheap. However, the development of omics tools tends to be biased, in particular for microbes. The momentum is lost as the technology rapidly changes, and the front line of researchers quickly moves on to the latest and greatest. For this reason, bacteria get a disproportionate amount of attention as technologies develop, and tools for genomes are much more abundant than tools for transcriptomes.

But *metatranscriptomics*, or the measurement of the expression levels of an entire community from a single sample, has an important role to play in microbial oceanography. We often can *only get* a single sample easily, and there’s an enormous amount of uncultured diversity present in those samples. For that reason, marine metatranscriptomics have massive potential both to tell us about organisms that we aren’t able to cultivate in the lab, and to tell us how the *expression* of various genes changes over time. This simultaneously tells us what microbes are present in a sample, and what biogeochemical roles they might be performing.

I am interested in marine microbial eukaryotes, or protists, which present the secondary challenge that a lot of omics tools are not developed for eukaryotic organisms. For this reason, I have developed *euk*`rhythmic`, a metatranscriptomic pipeline that consolidates the output of multiple individual assemblers to produce a cohesive assembly process that can be used for downstream analysis and posing meaningful biological and oceanographic questions.