# NGC 3526 FAST Spectroscopic Reduction Project
This repository contains the reduction and analysis workflow for FAST spectroscopic observations of NGC 3526.
Repository Contents
NGC_3526_FAST_reduction_project_GitHub_ready.ipynb
Main reduction and analysis notebook
NGC3526DATA.fits
Science target FITS file
COMP.fits
Arc lamp comparison spectrum used for wavelength calibration
flats_biases/
Folder containing flat-field and bias calibration FITS files
Required Data Files
The calibration files (biases and flats) are too large to store directly in GitHub and must be downloaded separately.
Download them from:
Google Drive calibration folder
After downloading, place the files into a folder named:
flats_biases/
in the root of the repository.
Your repository structure should look like:
repository/
├── NGC_3526_FAST_reduction_project_GitHub_ready.ipynb
├── NGC3526DATA.fits
├── COMP.fits
└── flats_biases/
    ├── bias1.fits
    ├── bias2.fits
    ├── flat1.fits
    ├── flat2.fits
    └── ...
Running the Notebook
Open the notebook in:
Jupyter Notebook
JupyterLab
Google Colab
Then run the cells in order.
The notebook has been configured to:
read NGC3526DATA.fits directly from the repository root
read COMP.fits directly from the repository root
access calibration frames from flats_biases/
No Google Drive mounting is required.
Python Dependencies
Required packages include:
numpy
matplotlib
astropy
scipy
Install with:
pip install numpy matplotlib astropy scipy
Notes
This project was adapted from a Google Colab workflow into a GitHub-compatible structure for reproducible analysis and submission purposes.
