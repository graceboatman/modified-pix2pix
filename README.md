# modified-pix2pix
pix2pix Pytorch Implementation

<img src='imgs/test_image.png' align="right" width=384>


We followed the pix2pix model architecture as suggested by the authors in [Original Paper](https://arxiv.org/abs/1611.07004) with the following changes: <br>
*Dropout at only first 3 layers of decoder <br>
*Discriminator with receptive field size of 1, 70, 142, and 286

Our implementation includes: <br>
*Skip connections in the generator <br>
*Easy to select and modify discriminator receptive field size

