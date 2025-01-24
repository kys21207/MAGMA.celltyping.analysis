# MAGMA.celltyping.analysis

## Install using docker
docker pull ghcr.io/neurogenomics/magma.celltyping
docker run -it -v $(pwd):$(pwd) -v $(pwd) ghcr.io/neurogenomics/magma.celltyping:latest /bin/bash
Run library(MAGMA.Celltyping) in R
## download MAGMA
Extract and install MAGMA
Set the path to the MAGMA executable in R
library(MAGMA.Celltyping)
set_magma_path("/path/to/magma")


