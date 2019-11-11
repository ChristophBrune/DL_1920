
## DL_19/20: Deep Learning - From Theory to Practice <br> Christoph Brune
   
This repository contains the programming exercises for the Deep Learning course of 2019/2020 at the University of Twente.
   
## Introduction to Colab
During this course we will be using [Google Colab](https://colab.research.google.com/github/ChristophBrune/DL_1920/blob/master/codes/1_tutorial/lab00_setup/Hello%20Colab.ipynb) for the programming exercises. Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud. Its main advantage is that Colab offers the possibility to run your code on high-end GPU's which are well suited for Deep Learning models and can speed up your programs significantly. Also, most of the Python packages that we will be using are already installed in this environment. 

If you prefer to do offline development outside of Colab you need to install Python and Jupyter on your own laptop, as well as the relevant Python packages. Below there are instructions on how to do this. The GPU on your laptop is often not good enough to speed up the computations done in the models, so we recommend to still use Colab for this. The easiest way to interact with Colab is to save your code on Google Drive. It is therefore recommended to use git to clone this repository into a folder that is synchronized with Drive (see instructions below). Your student account is also a Google account so you should already have access to Google Drive. 

## Local Python installation
<br>

Follow the following instructions to install Miniconda and create a Python environment for the course:

1. Download the Python 3.7 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/ChristophBrune/DL_1920`.
1. Go to folder DL_1920 with `cd DL_1920`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note that the environment installation may take some time.  


   Notes: <br>
      The installed conda packages can be listed with `conda list`.<br>
      Some useful Conda commands are `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
      Add a python library to the Python environment: `conda install -n DL_1920 numpy` (for example)<br>
      Read [Conda command lines for packages and environments]<br>
      Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf




<br> 
<br> 

## Running local Python notebooks 
<br>


1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Windows: `activate deeplearn_course`, macOS, Linux: `source activate deeplearn_course`.
1. Download the python notebooks by direct downloads from the next section or with GitHub with the command `git pull`. 
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the exercise folder, for example `DL_1920/codes/1_tutorial/lab01_python`.

[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>



