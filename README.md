# Machine Learning in Finance with Python - Part 2: Introduction to Machine Learning

Author: Ankush Agarwal, University of Glasgow

## Units

This introductory course consists of five units. Each unit corresponds
to one interactive Jupyter notebook, which is also available
as a static PDF file. 

| Unit | Title | PDF | Google Colab |
|------|-------|-----|--------------|
| 1    | Language and NumPy basics | [PDF](latex/unit01.pdf) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit01.ipynb) |
| 2    | Control flow and list comprehensions | [PDF](latex/unit02.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit02.ipynb) |
| 3    | Reusing code - Functions, modules and packages | [PDF](latex/unit03.pdf) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit03.ipynb) |
| 4    | Plotting | [PDF](latex/unit04.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit04.ipynb) |
| 5    | Advanced NumPy | [PDF](latex/unit05.pdf)  | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit05.ipynb)
| 6    | Random number generation and statistics | [PDF](latex/unit06.pdf) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit06.ipynb) |
| 7    | Handling data with pandas | [PDF](latex/unit07.pdf) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit07.ipynb) |
| 8    | Data input and output | [PDF](latex/unit08.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit08.ipynb)
| 9    | Introduction to unsupervised learning | [PDF](latex/unit09.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit09.ipynb)
| 10    | Introduction to supervised learning | [PDF](latex/unit10.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit10.ipynb)
| 11    | Error handling (optional) | [PDF](latex/unit09.pdf) |  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/richardfoltyn/MLFP-ECON5130/blob/main/lectures/unit09.ipynb) |


***

## Installation

### Running without installation

Click on the ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)
    icon next to each notebook. This will immediately open the notebook
    in [Google Colab](https://colab.research.google.com), but you need
    a Google account to run anything and importing custom modules will not work.

### Running locally

#### Download the repository contents

If you are familiar with git, clone the repository:
```bash
git clone https://github.com/richardfoltyn/MLFP-ECON5130.git
```
Otherwise, download the contents as a ZIP file by clicking on
![Code](images/gh-code.png) above.

#### Install Anaconda

On Windows, you need to install a local Python environment such as 
[Anaconda](https://www.anaconda.com/products/distribution). On Linux,
your distribution comes with Python but the required packages are most likely
outdated, so it is still recommended installing Anaconda.

##### Windows

Once Anaconda is installed, click on _Jupyter Notebook_ in the Start menu
and navigate to where you extracted the repository contents. Select
`index.ipynb` to run the main notebook.

![Jupyter Notebook](images/conda-start.png)

##### Linux

You need to create a new Python environment which contains all the 
required packages. You can use the specification provided in [environment.yml](environment.yml)
to accomplish that:
```bash
conda env create -f environment.yml
```
Activate the virtual environment you just created:
```bash
conda activate MLFP
```
To start the Jupyter notebook server, navigate to where you extracted
the repository contents and run
```bash
cd path/to/repository
jupyter notebook index.ipynb
```
***
