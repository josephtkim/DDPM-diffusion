# DDPM
DDPM (Denoising Diffusion Probabilistic Models) implemented in PyTorch.

Based on the paper: https://arxiv.org/abs/2006.11239.

Inspired by the original implementation: https://github.com/hojonathanho/diffusion/tree/master and the pytorch implementation by Phil Wang: https://github.com/lucidrains/denoising-diffusion-pytorch.

Trained on the Flowers102 dataset: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/.

## Results:
### Settings
epochs: 200  
batch size: 32  
image size: 64x64  
timesteps: 1000  
learning rate: 0.0002  
loss function: Huber loss  
optimizer: Adam, default values  

TODO: Gif of results
