************* 
This package is a fork from https://github.com/Irrationone/copynumber with minor modification for supporting R-4.
*************

Copynumber with species agnostic pcf
====================================
This repository is forked from:
https://github.com/Bioconductor-mirror/copynumber

I have made changes to pcf.r function to make it species/build agnostic in following feature branch
https://github.com/sb43/copynumber/tree/feature/species_agnostic

pcf function now accepts user supplied cytoband file.

All the chromosomes are now referred by its index values.

Original chromosomes names were reassigned to index before returning the processed results.

Same logic can be applied to other functions wherever required.



