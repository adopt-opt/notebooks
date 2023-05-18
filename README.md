# Jupyter Notebooks accompanying ADOPT

## About



## Installation Instructions

To install the required dependencies for the notebooks please first create the environment configuration suited to your
computational environment by merging the respective configurations. E.g. for a GPU-based environment

```bash
conda-merge environment.common.yml environment.gpu.yml > environment.yml
```

Before we can then install the conda environment defined in `environment,yml`

```bash
conda env create -f environment.yml
```

and then activate the environment with

```bash
conda activate adopt-notebooks
```

After which you should be able to either launch a 
[local Jupyter server](https://blog.jupyter.org/jupyterlab-desktop-app-now-available-b8b661b17e9a), or run the notebooks
inside of your IDE.

## Content

#### Jaxfluids
* [Small Cylinder Flow Environment](./jaxfluids/debug_example.ipynb)

#### Design Optimization
* [Design Optimization Objective](./design-optimization/design_object_eval.ipynb)

#### Container SSH / K8s

* [Access with Container SSH](./k8s-usage/container_ssh.ipynb)
