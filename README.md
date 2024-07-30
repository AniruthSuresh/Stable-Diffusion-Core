# Stable-Diffusion-Core

`Stable-Diffusion-Core` is a comprehensive implementation of the Stable Diffusion model from scratch. This repository includes the core components necessary for training and deploying diffusion models, including encoders, decoders, CLIP encoding, and U-Net architectures.


### Installation and Setup

1. Clone the git repo :
   ```bash
   git clone https://github.com/AniruthSuresh/Stable-Diffusion-Core.git
   cd Stable-Diffusion-Core

2. Create the conda environment (tennis in this case) using the provided `env.yml` file and activate it:
   
   ```bash
   conda env create -f env.yml
   conda activate simpleddpm

3. To get the final output :
   ```bash
   cd src
   python3 check.py
