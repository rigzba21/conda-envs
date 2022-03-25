# conda-envs
A repo for different Conda environments to use.

## Install (mambaforge) on Linux:
```bash
mkdir -p /opt/conda && chown -R $USER:$USER /opt/conda

wget https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Linux-x86_64.sh && \
bash Mambaforge-Linux-x86_64.sh -u -p /opt/conda
```

Create an environment:
```bash
# create the environment
conda env create --file docker-stacks.yaml --name docker-stacks

# activate the environment
conda activate docker-stacks

# verify conda packages
conda list --explicit

# verify pip packages
pip list
```
