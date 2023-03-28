### 1. Anaconda
Download and install [Anaconda](https://www.anaconda.com/products/individual#Downloads) with default settings.

### 2. Git
If you are using Windows, download and install [Git](https://git-scm.com/) with default settings.<br>
If you want to know what Git is, read the first section of this [website](https://en.wikipedia.org/wiki/Git).

### 3. PyMC
From the **Start** menu, search for and open **Anaconda Prompt**. (if you are using macOS or Linux, please let me know)<br>
Follow the instruction on [PyMC website](https://www.pymc.io/projects/docs/en/stable/installation.html). It will let you create a fresh conda environment and install packages you need<br>
If you want to use PyMC, you should active the conda environment first by type the following in your **Anaconda Prompt** window:
```
conda activate pymc_env
```
If you are interested in managing your conda environments, see [Here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

### 4. Jupyter Notebook + Other Packages
Open and type the following in your **Anaconda Prompt** window:
```
conda activate pymc_env
conda install -c conda-forge notebook
```
If you want more information about Jupyter Notebook, see [Here](https://jupyter.org/).<br>
Let's install other packages needed for the tutorial.
```
conda install -c conda-forge pandas matplotlib scikit-learn openpyxl
```


### 5. Clone this repository to your local machine
Open **Anaconda Prompt** and change your current directory to the location where you want to have the local copy of this repository.<br>
For example, if your current directory is "C:\Users\Seungjae Lee" and you want to have the local copy at "C:\example" you should type the following in your **Anaconda Prompt** window:
```
cd ..
cd ..
cd example
```
Note that you should have "example" folder. If you are interested in Windows Command Prompt commands, see [Here](http://www.cs.columbia.edu/~sedwards/classes/2015/1102-fall/Command%20Prompt%20Cheatsheet.pdf)


Then, type
```
git clone https://github.com/sleebldg/Bayesian-Modelling.git
```
Now, you have a new folder named "Bayesian-Modelling".
If you are interested in using GitHub, take a look at [Here](https://guides.github.com/activities/hello-world/). Also, you can use this [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) (there are many different cheat sheets on the internet.

### 6. Start Jupyter Notebook
Open **Anaconda Prompt** and change your current directory to the location where you have the local copy of this repository (or it's parent directory).<br>
Activate the "pymc_env" environment
```
conda activate pymc_env
```
Then start Jupyter Notebook by typing
```
jupyter notebook
```
