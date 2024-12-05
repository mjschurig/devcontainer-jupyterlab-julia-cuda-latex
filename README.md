# devcontainer-jupyterlab-julia-cuda-latex
Dev container using features for python, jupyterlab, julia and latex. Pre-installed julia language server, matlab proxy etc.

## Quickstart

- [open the devcontainer](https://code.visualstudio.com/docs/devcontainers/tutorial)
- Go to localhost:8888
- Type in your token

## Setup

### Token

Change the token in docker-compose.yml

`environment:
      JUPYTER_TOKEN: "Test1234!"`

to another value.

### GPUs

[Set the GPU usage](https://docs.docker.com/compose/how-tos/gpu-support/) in docker-compose.yml

### Julia

julia-init.jl is run on every build of the container. Add Julia packages there.

### Python

python-init.sh is run on every build. Add pip packages there.