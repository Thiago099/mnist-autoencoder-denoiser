# Install Miniconda

https://docs.anaconda.com/miniconda/miniconda-install/

# Run the following commands on the miniconda terminal

```bash

conda create --name torch python=3.12.2

conda install -c conda-forge cudatoolkit=12.1 cudnn=8.9.7
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

conda deactivate
conda activate torch

conda update Pillow

pip install tqdm
pip install imageio
pip install "numpy<2"

```