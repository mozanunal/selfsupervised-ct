# Self-Supervised Training for Low-Dose CT Reconstruction

## Reference

## Installation

Create the environment and install dependencies

```sh
conda create env --name py37 python=3.7
pip install dival==0.6.1 pytorch==1.7 scikit-image==0.18.1
pip install https://github.com/odlgroup/odl/archive/master.zip --upgrade
```

Install the package in editable mode

```sh
pip install -e .
```

## Experiments

Run baselines
```
cd self_supervised_ct/experiments
python baseline_ellipses.py
python baseline_lodopab.py
```