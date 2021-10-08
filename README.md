# AI4Omics - Practical Session
This session aims to provide you practical skills in machine learning applied to omics data.

In this lab, we will use **transcriptome data** (i. e. expression levels of genes) of colon normal and tumour samples. Our goal will be to create a machine learning **classification algorithm** to predict whether a sample of colon tissue is normal or tumoral from its gene expression profile.

The lab is performed using **Python** programming language and **scikit-learn** package.

To follow the exercises you don't need to have a deep knowledge of Python. The session is adapted for beginners. Nevertheless, you are supposed to have some general programming skills for data analysis, not necessary with Python.  

## Prerequisites before we start  

Please install the following software on your computer:

- Python 3 (version 3.8 or higher)
- Python packages: pandas, numpy, scikit-learn, seaborn, matplotlib, notebook (or jupyterlab) 

### Installation of Python

Python can be downloaded and installed from https://www.python.org/downloads/.

### Installation of packages

Use `pip` to install packages with the following command:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib notebook
```
If you have already *Anaconda* or *Miniconda*, use `conda` command instead of `pip`:

```bash
conda install pandas numpy scikit-learn seaborn matplotlib
conda install -c conda-forge notebook
```

## Step 1: Download session materials

Please download the session materials from this Github repository on you computer. 

If you are familiar with `git`, you may use `git clone` command.

```git
git clone https://github.com/epimed/ai4omics-practical-session.git
```

![git clone repository](/images/git_clone.png)

Otherwise, simply download the whole repository in one ZIP archive and then extract the content to your working directory. 

![download repository](/images/git_download_marked.png)

## Step 2: Check the presentation of machine learning for omics if necessary

Be sure that you have already followed the regular class on machine learning for omics. If not, please watch first these videos which show a general machine learning pipeline and some common classification models.  

##### Part 1. Main challenges of machine learning for omics (19 min)

[![Part 1. Main challenges of machine learning for omics](https://img.youtube.com/vi/1C26bgWfsw4/0.jpg)](https://www.youtube.com/watch?v=1C26bgWfsw4)

##### Part 2. Example of leukemia classification using machine learning (17 min)

[![Part2. Leukemia classification using machine learning](https://img.youtube.com/vi/u_47GUetPFA/0.jpg)](https://www.youtube.com/watch?v=u_47GUetPFA)

## Step 3: Proceed to practical session

We will use the data of colon cancer stored in `colon_cancer.csv` file in `data` directory, and the code of the exercises in `notebook` directory.

To start, go to `notebook`directory on your computer and lunch *Jupyter Notebook* of the first exercise (task1):

```bash
jupyter notebook task1.ipynb
```

The task will normally be automatically loaded in the web browser at `http://localhost:8888/notebooks/task1.ipynb`. 

You can alternatively use *Jupyter Lab* which proposes a more complete web-based user interface to manage several notebooks as well as other types of document (HTML, text, markdown etc.):

```bash
jupyter lab
```

Please follow the instructions in the notebooks.

The solutions will be available later in this repository and also explained and commented in a video format (coming soon).