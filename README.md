
# genomicWidgets

<!-- badges: start -->
<!-- badges: end -->

A collection of functions to analyze quantitatively SCNA and methylation data, together with some other useful functions for proteogenomics analysis.

## Installation

``` r
# install.packages("devtools")
devtools::install_github("bzhanglab/genomicWidgets")
```

## Usage

***weightAveChr*** - uses a weight sum method to calculate the chromosome instability. 

This can be applied to whole genome to calculate the genome-wide chromosome instability or applied to a specific chromosome(s) and genomic range(s) to calculate the SCNA intensities for this local regions.

*citation*: Vasaikar, S et al. Cell. 2019 May 2;177(4):1035-1049.e19. doi: 10.1016/j.cell.2019.03.030


***plotCNV*** - plots the SCNA data as heatmap. 

This is useful to show the SCNA landscape for all the samples in the cohort. Alternatively, the user can specify chromosome(s) and genomic range(s) for the heatmap to focus on the local SCNA intensity.

*citation*: Dou, Y et al. Cell. 2020 Feb 20;180(4):729-748.e26. doi: 10.1016/j.cell.2020.01.026

***probe2gene*** - converts the probe-level DNA methylation data into gene-level DNA methylation, using the probe annotation from EPIC.

*citation*: Dou, Y et al. Cell. 2020 Feb 20;180(4):729-748.e26. doi: 10.1016/j.cell.2020.01.026