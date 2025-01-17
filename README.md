# PyUltraLight
PyUltraLight Repository

# Installation
```
conda create -n pyultralight2 python=2

conda activate pyultralight2

conda install jupyter

python -m ipykernel install --user --name pyultralight2 --display-name "pyultralight2"

cd ~/opt/miniconda3/envs/pyultralight2/compiler_compat

mv ld ld.bak

pip install numpy numexpr numba h5py pyfftw matplotlib multiprocessing

cd ~/projects/working/

git clone https://github.com/bunnyandbear/PyUltraLight.git

pynote
```
# Prerequisites

In order to run the Jupyter notebook, a number of Python prerequisites must first be installed. The full list of modules required by the main code and the notebook is:

numpy, numexpr, numba, h5py, pyfftw, time, sys, os, matplotlib, math, multiprocessing.

Note: Errors may be encountered for older matplotlib versions. Please ensure you have the latest version:
pip install --upgrade matplotlib

# More information

Instructions on basic setup and usage can be found here:
http://cosmology.blogs.auckland.ac.nz/pyultralight/

The complete code release paper can be found here:
https://arxiv.org/pdf/1807.04037.pdf
