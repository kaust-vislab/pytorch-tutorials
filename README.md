[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kaust-vislab/pytorch-tutorials/master?urlpath=lab)

# PyTorch tutorials

Collection of Jupyter notebooks demonstrating best-practices for using PyTorch on GPU accelerated hardware. 

* Demonstrate end-to-end GPU accelerated ML workflow using PyTorch to train various DNN achitectures.
* Demonstrate distributed, GPU accelerated training capable of scaling to clusters of GPUs.

## Using Conda

Create the environment...

```bash
$ conda env create --prefix ./conda-env --file environment.yml
```

...then activate the environment...

```bash
$ conda activate ./conda-env
```

...then launch the JupyterLab server.

```bash
$ jupyter lab
```
