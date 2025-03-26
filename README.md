# *Nitrobacter vulgaris* characterization study
Data and code to accompany the study, "Comparative physiological and genomic characterization of a novel Nitrobacter vulgaris strain from a nitrate-contaminated subsurface" by Flinkstrom et al, 2025.
## Contents
* `Growth-curves/` contains data from various growth experiments and code for plotting growth curves and calculating growth parameters.
* `Microrespirometry/` contains data and plotting code for the microrespirometry work.
* `Genomics/` contains data and code for extracting operons and gene sequences from genbank files.
* `NOB_environment.yml` file contains the description of the Conda environment used for data processing, except for the creation of operon synteny plots which use [Clinker](https://github.com/gamcil/clinker) which should be done in a separate environment as described in the Clinker installation procedure.
