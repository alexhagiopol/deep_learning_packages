## Deep Learning Packages

Installation of Python packagages needed for 
deep learning software development. I tested this installation 
procedure on Ubuntu 16.04 and Mac OS X 10.11.6 (El Capitan).

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
   
Create a conda environment according to YAML file:

    conda env create -f environment.yml

Activate the environment to work inside of it in the current terminal window:

    source activate deep-learning
    
OPTIONAL: You can now train a real neural network to test that your installation was successful:

    source activate deep-learning
    python cnn_tf_example.py

OPTIONAL: Verify that the carnd-term1 environment was created in your environments:

    conda info --envs
    
OPTIONAL: Cleanup downloaded libraries (remove tarballs, zip files, etc):

    conda clean -tp

OPTIONAL: To uninstall the environment:

    conda env remove -n deep-learning

    
