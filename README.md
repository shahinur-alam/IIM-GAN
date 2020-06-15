# Modified-SRGAN
This is a Pytorch impplementation of modified SRGAN algorithm. In this network, there are 12 residual blocks.

## Requirements
This code has been run in the following packages and versions-

* Anaconda (v 1.9.12)
* Python (v 3.7.5)
* PyTorch (v 1.3.1)
* cudatoolkit (v 10.1.243)
* numpy (v 1.17.4)
* opencv (v 3.4.2)

## Datasets
We have used the popular VOC2012 dataset. The dataset is available [here](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/). Download and extract in the data folder.

## Train
To train the model, run the train.py Don't forget to pass the argument such upscaling factor, epochs, etc.

## Test
To test a single image run the test_image.py pass the argument such as image name, scale factor, pytorch model, etc.

The loss, score, PSNR, SSIM values are in the statistics folder.

# Thank you very much
