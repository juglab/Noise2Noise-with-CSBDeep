# Noise2Noise Training with CSBDeep

A small example on how to use [CSBDeep](http://csbdeep.bioimagecomputing.com/) to train a network with the [Noise2Noise](https://arxiv.org/abs/1803.04189) training scheme.

## Setup
1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html)
2. Make sure your GPU supports CUDA 10.
3. Create a conda environment: `conda create -n n2n_SEM python=3.7`
4. Activate the environment: `source activate n2n_SEM`
5. Install packages:
```
pip install csbdeep
conda install tensorflow-gpu==1.15 # requires a sufficently new NVIDIA driver 
pip install jupyter
```
6. Start jupyter server: `jupyter notebook`

## How to cite:
The Noise2Noise training method was first described by Lehtinen _et al._:
```
@article{lehtinen2018noise2noise,
  title={Noise2noise: Learning image restoration without clean data},
  author={Lehtinen, Jaakko and Munkberg, Jacob and Hasselgren, Jon and Laine, Samuli and Karras, Tero and Aittala, Miika and Aila, Timo},
  journal={arXiv preprint arXiv:1803.04189},
  year={2018}
}
```

The training framework used in this example is [CSBDeep](https://github.com/CSBDeep/CSBDeep), which builds on [Tensorflow](https://www.tensorflow.org/).
