# Ned's Shed

## Installation

Taken from `v1.0.0` of [jupyter-cadquery](https://github.com/bernhard-42/jupyter-cadquery#a-using-conda):

```
conda env create -f ./environment.yml -n cq2-jl
conda activate cq2-jl

jupyter-labextension install --no-build $(cat labextensions.txt)
jupyter lab build --dev-build=True --minimize=False
```
