# MAGMA.celltyping.analysis

## Install using docker
docker pull ghcr.io/neurogenomics/magma.celltyping
docker run -it -v $(pwd):$(pwd) -v $(pwd) ghcr.io/neurogenomics/magma.celltyping:latest /bin/bash
Run library(MAGMA.Celltyping) in R
## download MAGMA
Extract and install MAGMA
Set the path to the MAGMA executable in R
library(MAGMA.Celltyping)
magma_install()

Save PAT 
apt update
apt install nano
nano .Renviron
Add Your GitHub PAT
GITHUB_PAT=your_personal_access_token
Save the file by pressing Ctrl + O, then press Enter to confirm. Exit the editor by pressing Ctrl + X.
Go to R and check with gh::gh_token()
