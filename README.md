# Conservation of uORF repressiveness and sequence features in mouse, human and zebrafish
## Guo-Liang "Chewie" Chew, Andrea Pauli and Alexander F. Schier
Data and iPython notebooks documenting all analysis for manuscript.

The provided data and annotations are sufficient for analysis and generation of all the figures in the published manuscript. However, the data has been preprocessed from existing data; the means to preprocess these data are in the iPython notebooks that are prefixed with numbers (e.g. 1. Mapping ribosome profiling and RNA-seq data.ipynb), rather than "Fig" (e.g. Fig 1 - Trends in uORF sequence characteristics - Mouse.ipynb).

Figures 1-3 have separate iPython notebooks for each of the 3 species datasets. This is to make plotting the data easier; reasonable x- and y-axis limits are already defined.

The following packages / versions were used.
biopython 1.65
matplotlib 1.4.3
numpy 1.10.2
pandas 0.16.2
RNA 2.1.7 (compiled from ViennaRNA version 2.1.7; "./configure --with-python" followed by "make" and "make install")
scikit-learn 0.16.1
seaborn 0.6.0
statsmodels 0.6.1
weblogo 3.4