# PyTorch GPU tutorials

Collection of Jupyter notebooks demonstrating best-practices for using PyTorch on GPU accelerated hardware.

## Using Conda

Create the environment...

```bash
$ conda env create -f environment.yml
```

...then activate the environment...

```bash
$ source activate $(head -1 $environment.yml | cut -d' ' -f2)
```

...then launch the Jupyter notebook server.

```bash
$ jupyter notebook
```
