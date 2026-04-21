# Singular Value Decomposition for the Inverse problem

**[summary](#summary) | [setup](#setup) | [resources](#resources) | [license](#license)**

# Exploring the physics of DC resistivity

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lheagy/2026-guest-lecture-csm/main)

[![License](https://img.shields.io/github/license/lheagy/2026-guest-lecture-csm.svg)](https://github.com/lheagy/2026-guest-lecture-csm/blob/main/LICENSE)

## Summary

This notebook app is designed to let users explore using SVD to solve the inverse problem for straight ray tomography.


## Setup

There are a few things you'll need to use this app on your own computer:

1. A working Python installation. I recommend using [Miniforge](https://github.com/conda-forge/miniforge), but you can also use [Anaconda](https://www.anaconda.com/download)
2. To install the [conda environment](./environment.yml)
3. A web browser that works with Jupyter
   (basically anything except Internet Explorer)

Alternatively, you can run this notebook on the cloud with binder: https://mybinder.org/v2/gh/lheagy/2026-guest-lecture-csm/main

**Windows users:** If you are using Anaconda, when you see "*terminal*" in the instructions,
this means the "*Anaconda Prompt*" program for you.

### Step 1: Python

Install Python on your machine. I recommend using [Miniforge](https://github.com/conda-forge/miniforge), but you can also use [Anaconda](https://www.anaconda.com/download)

If you are looking for tutorials, you can take a look at these videos:
for [Windows](https://youtu.be/FdatS_NKVrM)
and [Linux](https://youtu.be/3ncwbHyZeAg)

This will get you a working Python 3 installation with the `conda` package
manager. If you already have one, you can skip this step.

### Step 2: Download the notebook and code

To access the notebooks, there are 3 options (in order of preference):
1. You can download a zip file containing https://github.com/lheagy/2026-guest-lecture-csm/archive/refs/heads/main.zip.
2. You can run the notebooks online with binder through: https://mybinder.org/v2/gh/lheagy/2026-guest-lecture-csm/main

If you download the zip file, unzip it, and then open up a terminal in the `2026-guest-lecture-csm` directory.

### Step 3: Create the conda environment

With an open terminal in the `2026-guest-lecture-csm` directory, create the `2026-guest-lecture-csm` conda environment using the following:
```
conda env create -f environment.yml
```
and activate the environment
```
conda activate 2026-guest-lecture-csm
```

### Step 4: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks
```
jupyter lab
```
Jupyter will then launch in your web browser.

## Resources

**Resources on SimPEG**
- [Docs](http://docs.simpeg.xyz/)
- [Mattermost chat](https://mattermost.softwareunderground.org/simpeg)



## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).
