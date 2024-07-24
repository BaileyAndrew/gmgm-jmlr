# GmGM

This is the code repository for the paper (TODO: LINK).  It does not include the data used; namely the COIL-20 dataset and the two scRNA-seq datasets referenced in the paper.

To view the code used for generating figures in the paper, see:

Figure 2: `synthetic-data.ipynb`
Figure 3: `synthetic-data.ipynb`
Figure 4: `synthetic-data.ipynb`
Figure 5: `coil.ipynb` (uses COIL-20 dataset)
Table 5: `coil.ipynb`
Figure 6: `coil.ipynb`
Figure 7: `create-graph-***.ipynb` first to generate results **for each model**, and then `scrna-plots` to compile the results into the figure in the paper (uses Cillo et al's 2020 head-and-neck cancer dataset)
Table 6: `create-graph-***.ipynb` to get model results, `analyze-graph-gmgm-***` to create cluster results, which are stored in `results-gmgm-***` folders - these folders are included in this repository so you can view them without re-running the code
Figure 8: `million-cell.ipynb` (data generation) and `million-cell-analyze.ipynb` (plot generation) (using Yazar et al's 2022 million-cell dataset)
Table 7: `million-cell.ipynb` (data generation) and `million-cell-analyze.ipynb` (generates `million-cell` folder of results, which has been pre-generated and included in repo)