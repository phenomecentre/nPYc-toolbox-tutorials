# nPYc-toolbox-tutorials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/phenomecentre/nPYc-toolbox-tutorials/master)

The tutorials in this repository use Jupyter notebooks to demonstrate the application of the [nPYc-Toolbox](https://github.com/phenomecentre/nPYc-Toolbox) for the preprocessing and quality control of exemplar LC-MS, NMR and targeted NMR (Bruker IVDr) metabolic profiling datasets. These tutorials work through each step in detail, with links to relevant documentation, hosted on [Read the Docs](http://npyc-toolbox.readthedocs.io/en/latest/index.html).

For full details on installation and the tutorial datasets see [Installation and Tutorials](https://npyc-toolbox.readthedocs.io/en/latest/tutorial.html), however, in brief, this repository provides:

 - Preprocessing and Quality Control of LC-MS Data with the nPYc-Toolbox.ipynb: Jupyter notebook tutorial for LC-MS RPOS (XCMS) data
 - Preprocessing and Quality Control of NMR Data with the nPYc-Toolbox.ipynb: Jupyter notebook tutorial for NMR (Bruker) data
 - Preprocessing and Quality Control of Targeted NMR Data (Bruker IVDr) with the nPYc-toolbox.ipynb: Jupyter notebook tutorial for targeted NMR (Bruker IVDr) data
 
Alongside all required exemplar datasets and associated files:

 - DEVSET U RPOS xcms.csv: feature extracted (XCMS) LC-MS RPOS data
 - DEVSET U 1D NMR raw data files: folder containing the 1D NMR raw data files and the Bruker IVDr xml quantification files
 - DEVSET U RPOS Basic CSV.csv, DEVSET U 1D NMR Basic CSV.csv and DEVSET U 1D NMR IVDr Basic CSV.csv: CSV files containing basic metadata about each of the acquired samples for each dataset
 
 The dataset used in these tutorials (DEVSET) is comprised of six samples of pooled human urine, aliquoted, and independently prepared and measured by ultra-performance liquid chromatography coupled to reversed-phase positive ionisation mode spectrometry (LC-MS, RPOS) and 1H nuclear magnetic resonance (NMR) spectroscopy. Each source sample was separately prepared and assayed thirteen times. A pooled QC sample (study reference, SR) and independent external reference (long-term reference, LTR) of a comparable matrix was also acquired to assist in assessing analytical precision. For more information see the Metabolights Study [MTBLS694](https://www.ebi.ac.uk/metabolights/MTBLS694).
