**[usage](#usage) | [running the notebooks](#running-the-notebooks) | [issues](#issues)**

# Environmental Geophysics: Fundamentals & Applications
Simulation and inversion notebooks in 1D and 2D for Geoscience Without Border Projects in Myanmar.


## Usage

### locally

#### Step 1: Install Anaconda
To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/). Please download 
Python 3.7 or greater. 


#### Step 2: Download the apps
Once you have downloaded and installed anaconda, you can then download this repository through: https://github.com/simpeg-research/gwb-dc-inversions/archive/master.zip, and the unzip the directory somewhere convienent (e.g. your desktop). 

**Aside**

If you are familiar with `git`, you can clone this repository; from a command line (if you are on windows, please use the anaconda terminal that came with the installation)
run

```
git clone https://github.com/sgkang/uofm_envgp.git
```

#### Step 3: Install Dependencies

Open the anaconda prompt (if on windows) or a terminal otherwise.

Then `cd` into the `gwb-dc` directory. Note that you will need to replace `[path]` with the path to where you downloaded the apps to. You can find this by opening up a file-browser where you unzipped the directory and copying that path:

```
cd [path]/uofm_envgp
```

To setup your software environment, please use conda forge and install SimPEG: 

```
conda install -c conda-forge simpeg
```


#### Step 4: Launch Jupyter

You can then launch Jupyter

```
jupyter lab
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://em.geosci.xyz/_images/run_all_cells.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

If you are new to Python, I highly recommend taking a look at:
- [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/)
- [The Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

## Issues

Please [make an issue](https://github.com/sgkang/uofm_envgp/issues) if you encounter any problems while trying to run the notebooks.
