## Deep Learning Packages

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)
    
My version of Udacity's documentation for installation of Python packagages needed for 
Deep Learning software development. I tested this installation procedure on Ubuntu 16.04.

### Installation

Clone the repository:

    git clone git@github.com:alexhagiopol/deep_learning_packages.git
    cd deep_learning_packages
    
Install the latest version of Miniconda: 

Ubuntu:

    wget  https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
    bash Miniconda3-latest-Linux-x86_64.sh
    
Mac:

    brew install wget
    wget https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
    bash Miniconda3-latest-MacOSX-x86_64.sh
   
Create a conda environment according to the YAML file provided by Udacity:

    conda env create -f environment.yml

Activate the environment to work inside of it in the current terminal window:

    source activate carnd-term1
    
OPTIONAL: Verify that the carnd-term1 environment was created in your environments:

    conda info --envs
    
OPTIONAL: Cleanup downloaded libraries (remove tarballs, zip files, etc):

    conda clean -tp

OPTIONAL: To uninstall the environment:

    conda env remove -n carnd-term1

    
    