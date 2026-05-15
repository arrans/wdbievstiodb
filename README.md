Overview:

The notebook in this repo is a reference for use with the paper 'When Data Becomes Insight: Essential Visualisation Strategies to Increase Impact of Big Data'.
The notebook supports the reproducability of the results in the paper.

The notebook uses Jupyter notebooks, using Python code (version 3.9.7) to load, inspect and prepare the dataset from The Cancer Imaging Archive (TCIA). 
Anaconda Navigator version 2.1.4 was used to launch Jupyter Notebook version 6.4.5.
The notebook experiments with a range of data visualisation techniques with a focus on improving clarity and ease of interpretability.

Requirements:
- Install Python (free)
- Install Anaconda Navigator (free) in order to use Jupyter Notebooks
- Download datasets from National Lung Screening Trial(NLST) from The Cancer Imaging Archive(TCIA). https://www.cancerimagingarchive.net/collection/nlst/
You will need to download the files separately and update file paths as needed in the initial sections of the notebook to replicate the results.
File references for datasets:
1) nlst_780_canc_idc_20210527.csv maps to dataframe df_canc
2) nlst_780_ctab_idc_20210527.csv maps to dataframe df_ctab
3) nlst_780_ctabc_idc_20210527.csv mpas to dataframe df_ctabc
4) nlst_780_prsn_idc_20210527.csv maps to dataframe df_prsn
5) nlst_780_screen_idc_20210527.csv maps to dataframe df_screen

Setup:
- Clone this repository
- Open the jupyter notebook
- Update dataset file paths as necessary in the notebook so they point to your locally downloaded dataset files
- Run cells sequentially to replicate results
