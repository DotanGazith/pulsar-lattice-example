# pulsar-lattice-example

This repository contains an example of recovering the periodicity of PSR J0318+0253 (4FGL J0318.2+0254) using the lattice periodicity search approach described in (**paper**).

The Data was reduced from the Fermi-LAT database using fermitools, and some dedicated auxiliary functions.

Use the requirements file to set up the Python environment, although to install *g6k*, you might want to consult its respective repository (*https://github.com/fplll/g6k*).

## Creating an environment
```
git clone https://github/fplll/g6k
cd g6k
conda create --name g6k
conda activate g6k
conda install numba
pip install -r requirements.txt
conda install -c conda-forge fpylll
python setup.py build_ext --inplace
python -m pytest
```
