# conda-envs
A repo for different Conda environments to use.

## Environments:
#### Docker Stacks
A conda environment for testing Docker Stacks.

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

