


## Installation

Some commands I have run to set up the environment


scorpy and pypadf requirements

    conda deactivate
    conda create -n p3378 python=3.13 --yes
    conda activate p3378 --yes
    conda install numpy --yes
    conda install matplotlib --yes
    conda install h5py --yes
    conda install scikit-image --yes
    conda install regex --yes
    conda install numba --yes
    conda install ipython --yes
    conda install conda-forge::pyshtools --yes
    conda install conda-forge::pycifrw --yes

interfacing with euxfel data

    pip install extra_data
    pip install extra_geom

pyfai

    git clone https://github.com/silx-kit/pyFAI
    cd pyFAI
    pip install -r requirements.txt
    pip install . --upgrade

scorpy

    git clone https://github.com/YellowSub17/scorpy-pkg.git
    cd scorpy-pkg
    pip install -e .


## install ipython kernal

    python -m ipykernel install --user --name p3378 --display-name "Python (p3378)"




    


