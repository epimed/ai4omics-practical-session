# AI4Omics - Practical Session
This practical session aims to provide you practical skills in machine learning applied to omics data. 

We will use Python programming language with a machine learning framework `scikit-learn`. The exercises will be present in a format of Jupyter notebooks. If you are not familiar with these technologies, all instructions of installation and use will be provided. The session is adapted for beginners.

In this lab, we will use **transcriptome data** (i. e. expression levels of genes) of colon normal and tumor samples. Our goal will be to create a machine learning **classification algorithm** to predict whether a sample of colon tissue is normal or a tumor from its gene expression profile.

The practical session is composed of **two main tasks**. The first task (Task 1) aims to introduce you to a basic machine learning pipeline and to show how to create a simple classifier. In the second task (Task 2), you will be invited to create a logistic regression classification model for cancer diagnosis using omics data. The solutions for all the exercises will be available.

## Presentation of the practical session

Please watch the following video that presents the details of the practical session (9 min).

[![Practical session for omics data analysis by machine learning with scikit-learn](https://img.youtube.com/vi/KEYpxSzTS54/0.jpg)](https://youtu.be/KEYpxSzTS54)

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

### Download the session materials

Please download the session materials from this Github repository to your computer. 

If you are familiar with `git`, you may use `git clone` command.

```git
git clone https://github.com/epimed/ai4omics-practical-session.git
```

![git clone repository](/images/git_clone.png)

Otherwise, simply download the whole repository in one ZIP archive and then extract the content to your working directory. 

![download repository](/images/git_download_marked.png)


### Start a Jupyter notebook of the Task 1

We will use the data of colon cancer stored in `colon_cancer.csv` file in `data` directory, and the code of the exercises in `notebook` directory.

To start, go to `notebook` directory on your computer and load a *Jupyter Notebook* of the first exercise `task1.ipynb`:

```bash
jupyter notebook task1.ipynb
```

The task 1 will be automatically loaded in the web browser at `http://localhost:8888/notebooks/task1.ipynb`. 

You can alternatively use *Jupyter Lab* which proposes a more complete web-based user interface to manage several notebooks as well as other types of document (HTML, text, markdown etc.):

```bash
jupyter lab
```

## Task 1 - Basic Machine Learning Pipeline

Follow the instructions in the notebook `task1.ipynb` and watch the video below with step-by-step explanations of the Task 1 (16 min).

[![Task 1 - Basic machine learning pipeline with scikit-learn](https://img.youtube.com/vi/iRYuaHqV_o4/0.jpg)](https://youtu.be/iRYuaHqV_o4)

The solution of the Task 1 is also available in `task1_solution.ipynb` and  `task1_solution.pdf`.

## Task 2 - Logistic Regression Classifier

The second task is available in the file `task2.ipynb`.

Please following the instructions in the notebook and try to complete this task by yourself.

You can check the solution of the Task 2 with step-by-step explanations and comments in the video below (16 min).

[![Task 2 - Logistic regression with scikit-learn](https://img.youtube.com/vi/DlknLZvPb5w/0.jpg)](https://youtu.be/DlknLZvPb5w)

The solution of the Task 2 is also available in `task2_solution.ipynb` and `task2_solution.pdf`.
