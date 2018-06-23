Udacity Deep Learning Project 4
Using Generative Adversarial Networks to generate images of faces
See the Jupyter Notebook for full details.
Intended to run on Ubuntu Linux 16.04
AWS EC2 p2.xlarge GPU Compute Instance, image Deep Learning AMI with Source Code (CUDA9, Ubuntu)

To install the environment:

1) Install Miniconda like this:
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh

2) Create the environment:
conda-env create -f dlnd-gan-env.yml -n gan

