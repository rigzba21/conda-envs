# conda-envs
A repo for different Conda environments to use.

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
