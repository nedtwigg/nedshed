# Ned's Shed

## Installation

We are using `v1.0.0` of [jupyter-cadquery](https://github.com/bernhard-42/jupyter-cadquery), which you can run like so:

```
docker run -it --rm -v notebooks:/home/cq -p 8888:8888 bwalter42/jupyter_cadquery:1.0.0
```

Then open a browser to `localhost:8888`.

## Scripts

1. [POC](notebooks/POC.ipynb] tests CadQuery features for our diagonal-symmetry usecase.
2. [Floorplan](notebooks/Floorplan.ipynb] tests whether the shed can fit the things we want it to fit.
3. [Framing](notebooks/Framing.ipynb) frames out the walls in 2x4s (in-progress).
