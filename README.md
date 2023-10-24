[![DOI](https://zenodo.org/badge/527488004.svg)](https://zenodo.org/doi/10.5281/zenodo.10038512)

# Analysis reproduction repository for "MeerKAT radio observations of the neutron star low-mass X-ray binary Cen X-4 at low accretion rates"

![Field of view from MeerKAT](Figure1_2/Figure1.png?raw=true "Cen X-4 field with MeerKAT")

## Based on Van den Eijnden et al. (2022), MNRAS accepted.
The full paper, included updated versions can be found on https://arxiv.org/abs/2207.03962 (open access) and is included in this repository.

This reproduction reposity contains two Jupyter notebooks and all data products/images to reproduce the images and analysis in the above paper. In order to run the notebooks, check the software requirements below, clone the repository, and run through each cell. The motivations for the analysis are included to limited extend, but we refer to the full paper for all details.

The notebook includes the .fits images of all analysed MeerKAT observations, even though only one is plotted in the paper.

Please get in touch via email (jakob.vandeneijnden [at] st-hildas.ox.ac.uk) or github with questions.

If this repository is useful for your own research, in addition to citing the original paper, please consider including a note to this repository as well.

## Software requirements

To reproduce the analysis and figures, the notebooks are written in two python versions: Python 2.7 (Reproduction_Notebook_Python2.ipynb) and Python 3.9 (Reproduction_Notebook_Python3.ipynb). The former is included to perform the MCMC fits of the X-ray -- radio luminosity plane with linmix and to plot the radio images using aplpy. Python 2.7 is used due to compatibility issues in Python 3. The latter notebook is used for the other figures, e.g. the X-ray and radio light curves, and the X-ray -- radio luminosity plane.

We acknowledge the use of the "Radio/X-ray correlation database for X-ray binaries" by Bahramian et al. (2018) for this code. See https://github.com/bersavosh/XRB-LrLx_pub and https://zenodo.org/record/6972578#.YwNFQS2ZOL4 for more details.

The Python 2.7 notebook uses the following packages:

- numpy v1.15.4
- matplitlib v2.2.3
- scipy v1.1.0
- astropy v2.0.9
- linmix v0.1.0 [https://github.com/jmeyers314/linmix.git]
- aplpy v1.1.1 [https://github.com/aplpy/aplpy]

The Python 3.9 notebook uses the following packages:

- astropy v4.3.1
- pickle
- numpy v1.21.2
- matplitlib v3.4.3
- scipy v1.7.1










