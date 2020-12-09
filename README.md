# test_binder

Testing Jupyter Notebook binder

## Setup

```bash
cd test_binder/tutorials
conda env create -f environment.yml
```

**environment.yml**

```yaml
name: ntbk_env
channels:
  - conda-forge
  - bioconda
  - defaults
dependencies:
  - python=3.8
  - jupyter
```

``{bash}
conda activate ntbk_env      # start
conda deactivate             # stop
```

## Create a Notebook

```bash
conda activate ntbk_env
jupyter notebook               # Starts server
```
