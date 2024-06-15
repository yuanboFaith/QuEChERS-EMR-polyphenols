## Method development and validation for analysis of phenolic compounds in fatty complex matrices using enhanced matrix removal (EMR) lipid cleanup and UHPLC-QqQ-MS/MS

**This file documents the original R code constructed for various analysis.** The code and output can be accessed [here](https://yuanbofaith.github.io/QuEChERS-EMR-polyphenols/). 

See [**original article**](https://www.sciencedirect.com/science/article/abs/pii/S0308814621021026) published in *Food Chemistry*.

## Abstract

Reliable analysis of phenolic compounds in fatty matrices is a challenging task. In this work, a robust analytical method was developed and validated for 55 phenolic compounds employing QuEChERS (quick, efficient, cheap, easy, rugged and safe) and Enhanced Matrix Removal (EMR)-lipid cleanup in 96-well plates for sample preparation, coupled with ultra-high performance liquid chromatography with triple quadrupole mass spectrometry (UHPLC-QqQ-MS/MS). Seven high-fat matrices of pork brain, belly and liver; horse serum, beef, salmon and avocado were explored for method validation and led to promising stepwise recoveries of extraction, clean-up, drying-reconstitution of most analytes ranging from 75% to 113%, and with an accuracy of 78%∼117%, except for six catechin-analogues. The matrix removal efficiency of EMR was determined using UHPLC-quadruple time of flight (QTOF)-MS, and results indicated that 56%∼77% of co-extractives were removed. This method would be readily extended to wide range of applications demanding high-throughput and sensitive analysis of phenolic compounds in fatty samples.



## R Script Reference

The R code has been developed with reference to [**R for Data Science (2e)**](https://r4ds.hadley.nz/), and the official documentation of [**tidyverse**](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- **Data visualization** with **ggplot2** ([**tutorial**](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [**data viz. gallery**](https://www.databrewer.co/R/gallery)).

- [**Data wrangling**](https://www.databrewer.co/R/data-wrangling) with the following packages:
[**tidyr**](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [**dplyr**](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [**stringr**](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [**regular expression**](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [**purrr**](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [**tibble**](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.

