This is a README file to provide the information for files in this repo. The repo contains:

1. Jupyter notebook "CODES_PUBLISH.ipynb"
2. FISH_DATA_RH2014_ORIGINAL.xlsx
3. FISH_DATA_RH2014_UPDATED.xlsx
4. Misteli_pr_all_pairs.npy
5. README

The Jupyter notebook file `CODES_PUBLISH.ipynb` contains all the necessary codes used in the [paper](https://www.nature.com/articles/s41467-019-11897-0) to illustrate the methods we proposed to extract the subpopulation information from the FISH data. The files `FISH_DATA_RH2014...xlsx` contained in this folder are used to demonstrate our proposed methods for the CTCF loops. They are obtained from the Dropbox depository set up by the author of [1]. The permission are granted from the authors. For more information, please refer to this page https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!searchin/3d-genomics/FISH%7Csort:date/3d-genomics/0TI5sz4TyF4/iKCNK3jXAQAJ. The file `Misteli_pr_all_pairs.npy` contains the data from [4DN portal](https://data.4dnucleome.org/publications/80007b23-7748-4492-9e49-c38400acbe60/). The raw data is post-processed to drop duplicates.

### SOFTWARE DEPENDENCIES:
    * Python (v3.7)
    * Jupyter Notebook (v5.6.0)
    * Python Package:
        - numpy (v1.16.2)
        - scipy (v1.2.0)
        - pandas (v0.24.2)
        - matplotlib (v3.0.3)
        - lmfit (v0.9.13)
        - xlrd (v1.2.0)

### INSTALLATION GUIDE
    No installation is required to use the codes. Use jupyter notebook to open 'CODES_PUBLISH.ipynb'. The notebook contains all the codes. The notebook is constructed to contain a series of cells which can be executed individually. Follow the instructions in the notebook and execute the cells to generate the data and results. 

    NOTE: To execute a cell in the notebook, use "shift+return"

### INSTRUCTIONS FOR USE
    In the terminal, execute 'jupyter notebook' in the current directory. Then open the notebook file "CODES_PUBLISH.ipynb". This notebook contains all the codes which can reproduce the quantitative results shown in Fig.4/5/6 in the main text and Fig.S2/S3/S5 and Table.S1/S2/S3 in the Supplementary Information.

### DEMO
    ## Instruction to run on the data
        All the intructions are in the notebook. 
    ## Expected Output
        All expected outputs are in the notebook
    ## Expected run time for demo
        30 - 60 Minutes


### REFERENCE
1. Rao, Suhas SP, et al. "A 3D map of the human genome at kilobase resolution reveals principles of chromatin looping." Cell 159.7 (2014): 1665-1680.

2. Finn, Elizabeth H., et al. "Extensive Heterogeneity and Intrinsic Variation in Spatial Genome Organization." Cell 176.6 (2019): 1502-1515.
