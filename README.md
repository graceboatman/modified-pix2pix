# modified-pix2pix
pix2pix Pytorch Implementation

<img src='imgs/test_image.png' align="right" width=200>


We followed the pix2pix model architecture as suggested by the authors in the original [Paper](https://arxiv.org/abs/1611.07004) with the following changes: <br>
* Dropout at only first 3 layers of decoder <br>
* Discriminator with receptive field size of 1, 70, 142, and 286

Our implementation includes: <br>
* Skip connections in the generator <br>
* Added discriminator receptive field size options

<img src='imgs/architecture.png' align="center" width=500> <br>

<img src='imgs/discriminator.png' align="center" width=400>