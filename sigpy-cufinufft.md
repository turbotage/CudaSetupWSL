

## Install packages
we here assume you have created a conda environment setup in python 3.7 and if you are on wsl, that you have followed [CUDA Setup WSL](cuda-cuDNN-wsl.md)
```console
$ pip install cupy-cuda11x
$ pip install pycuda
$ pip install cufinufft
$ pip install sigpy
```


If ```  from cupy import cudnn ``` doesn't work perhaps this needs to be run
```console
$ python -m cupyx.tools.install_library --cuda 11.x --library cudnn
```