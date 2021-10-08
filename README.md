# AI4Omics - Practical Session
This session aims to provide you practical skills in machine learning applied to omics data.

In this lab, we will use **transcriptome data** (i. e. expression levels of genes) of colon normal and tumour samples. Our goal will be to create a machine learning **classification algorithm** to predict whether a sample of colon tissue is normal or tumoral from its gene expression profile.

The lab is performed using **Python** programming language and **scikit-learn** package.

## Before we start   

Please install the following software on your computer:

- Python 3 (version 3.8 or higher)
- Python packages: pandas, numpy, scikit-learn, seaborn, matplotlib, notebook (or jupyterlab) 

### Installation of Python

Python can be downloaded and installed from https://www.python.org/downloads/.

### Installation of packages

One Python is installed, use `pip` to install packages with the following command:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib notebook
```
If you have already *Anaconda* or *Miniconda*, use `conda` command instead of `pip`:

```bash
conda install pandas numpy scikit-learn seaborn matplotlib
conda install -c conda-forge notebook
```

## Step 1: Download session materials

Please download the session materials from this repository on you computer.  
