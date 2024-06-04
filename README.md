# Simulation of AAA+ motor

This repository contains the source codes and result datas for the simulation of AAA+ motor in 26S proteasome.

## Requirements

The entire project is based on Python and Jupyter Notebook. To open and run the source code in notebook files, a Python (3.8.15) and a Jupyter Notebook installation is required. The following Python packages are also required:

* numpy (1.22.4)
* matplotlib (3.6.2)
* scipy (1.7.3)
* numba (0.56.4)

We only tested the code under the versions of Python and packages mentioned above. Although it may still work under other versions, we recommend running the code with the same versions as our testing environment to ensure that all results can be reproduced correctly. 

If other versions of Python and packages are already installed, please use virtualenv or conda to create a virtual environment for this project.

## Files

* `model.ipynb`: Simulating the dynamic of AAA+ motor in human proteasome.
* `plot.ipynb`: Visualizing the simulation result. All plots are shown as the figures in our article.
* `model_stat.ipynb`: Calculating the probabilities of stochastic events. The plots are shown as figure 3A-D in our article.
* `result.dat`: Pre-calculated simulation results. New simulation results can be generated by `model.ipynb` and visualized by `plot.ipynb`

## How to use

The code can be obtained by running:

```bash
$ git clone https://github.com/diwu31415/ATPase_motor
```

or simply click "Code -> Download Zip" on this page.

After cloning or downloading and unpacking is complete, open the notebook files with your favorite Jupyter-supported editor (e.g. VScode with Jupyter plugin).

Afterward, you can browse and execute the code in the notebook files in the same way as you operate other notebook files.