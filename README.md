# Exoplanet Course at DTU Space
Exoplanet Course at DTU Space



## Install PLATON

git clone https://github.com/ideasrule/platon.git
cd platon
pip install -e .

## Install other packages

# Install h5py to read the data
pip install h5py 

# Install batman-package to fit the transit model
# Windows users may need to install "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
# Additional instructions:
# https://stackoverflow.com/questions/29846087/error-microsoft-visual-c-14-0-is-required-unable-to-find-vcvarsall-bat/55575792#55575792
# You may need to downgrade numpy to 1.26.0: pip install numpy==1.26.0
pip install batman-package  

# Install emcee to run the MCMC algorithm
pip install emcee

# Install tqdm to show progress bars
pip install tqdm