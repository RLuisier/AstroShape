# AstroShape
Statistical analysis of single-cell morphological changes over the time-course of astrocyte differentiation.

# Singe-cell morphological profiling and analysis of astrocytes during terminal differentiation.

This repository contains the source code to reproduce some of the figures of the manuscript entitled [Generation of morphologically distinct astrocyte subtypes from human iPSCs reveals a link between glial shape, function and reactivity](https://www.biorxiv.org/content/10.1101/2022.11.23.517728v1) by L Guetta, K O’Toole, P Suklai, P Urbanaviciute, Raphaelle Luisier, S Marzi, A Serio. The repository contains:

-   [Dependencies](#Dependencies)
-   [Repo Content](#Repo-Content)
-   [Samples description](#Samples_description)

## Dependencies
### R
Bioconductor version 3.16 (BiocManager 1.30.19), R 4.2.2 (2022-10-31)

The following R packages should be installed:<br>
ggplot2_3.5.0<br>
RColorBrewer_1.1_3<br>
colortools_0.1.5<br>
gplots_3.1.3.1<br>
RColorBrewer_1.1_3<br>
lme4_1.1_33

## Repo Content
* [data](./data): folder containing the data for examples matrix of gene expression; etc. Raw fluorescent microscopy data will be deposited publicly on EBI.
* [figures](./figures): folder containing the figures including those used for the manuscript.
* [Scripts](./scripts): `R`, `Python` and `Bash` custome code

## Samples description
Fluorescent micropscopy data. iPSC-derived astrocytes were cultured in 96-well plates for 21 days and fluorecent images were taken after 0, 1, 7, 14 and 21 days in culture. The cells were treated with the following three different treatment (except at day 0 where all wells are expected to be the same) were : 

1. **No treatment**: D1-D7.
1. **CNTF treatment**: A1-A7.
1. **BMP4 treatment**: B1-B7. 
1. **CNTF+BMP4 treatment**: C1-C7

Half of the astrocytes were transfected with a GFP under the CMV promoter which provides the highest expression activity in the broadest range of cell types. Only half of the plated cells contain the GFP in order to be able to detect cells. 

## Analysis and results
The analysis is presented in the [preprocessing analysis](https://htmlpreview.github.io/?https://github.com/RLuisier/AxonLoc/blob/main/1_overview_data.html) that relates to  Figure 1 and Supplementary Figure 1.

## Related publication
This work has been published in Genome Research (doi: 10.1101/gr.277804.123).








