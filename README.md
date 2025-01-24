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

## To save PAT 
		apt update
		apt install nano
		nano .Renviron
		Add your GitHub PAT like
		GITHUB_PAT=your_personal_access_token
		Save the file by pressing Ctrl + O, then press Enter to confirm. Exit the editor by pressing Ctrl + X.
		in R check with gh::gh_token()


