# Astronomy Denoising

A small example on how to use [CSBDeep](http://csbdeep.bioimagecomputing.com/) to train a network with the [Noise2Noise](https://arxiv.org/abs/1803.04189) training scheme.

## Setup
1. Install [miniconda]
2. Make sure your GPU supports CUDA 10.
3. Create a conda environment: `conda create -n astro python=3.7`
4. Activate the environment: `source activate astro`
5. Install packages:
```
pip install Pillow
pip install csbdeep
conda install tensorflow-gpu==1.15 # requires a sufficently new NVIDIA driver 
pip install jupyter
```
6. Start jupyter server: `jupyter notebook`
