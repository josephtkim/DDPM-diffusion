# DDPM
DDPM (Denoising Diffusion Probabilistic Models) implemented in PyTorch.

Based on the paper: https://arxiv.org/abs/2006.11239.

Inspired by the original implementation: https://github.com/hojonathanho/diffusion/tree/master and the pytorch implementation by Phil Wang: https://github.com/lucidrains/denoising-diffusion-pytorch.

Trained on the Flowers102 dataset: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/.

## Results:
### Settings
epochs: 200  
groups in group norm: 8  
batch size: 64  
image size: 64  
beta_1: 0.0001  
beta_T: 0.02  
timesteps: 1000  
learning rate: 0.0002  
loss function: Huber loss  
optimizer Adam (default values)

![final](./experiment1.png)

![animation](./experiment1.gif)


|         | ResNet-34 |  ResNet-50 |
|------------------------|----------------|--------------------------|
| # of Trainable Params  | ![final](./experiment1.png) | ![final](./experiment1.png) |
| Test Accuracy |  |  |
