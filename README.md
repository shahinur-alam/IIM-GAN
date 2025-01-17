# IIM-GAN
This is a Pytorch impplementation of IIM-GAN algorithm. In this network, there are 12 residual blocks.

## Requirements
This code has been run in the following packages and versions-

* Anaconda (v 1.9.12)
* Python (v 3.7.5)
* PyTorch (v 1.3.1)
* cudatoolkit (v 10.1.243)
* numpy (v 1.17.4)
* opencv (v 3.4.2)

## Train and Validation Datasets
We have used the popular VOC2012 dataset. The dataset is available [here](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/). Download and extract in the data folder.

## Test samples
The test data are directly captured from the integral imaging microscopic system. In the original experimental setup, we use an Olympus BX41TF microscope with 10x magnification. An MLA composed of 100×100 lenses is used for IIM; each lens diameter and focal length are 2.4 mm and 125 μm, respectively. The image is captured using the Point Grey GS3-U3-41C6C-C, 1-inch CMOS sensor through the NIKON 20 mm lens. This sensor can capture 4.1 megapixels of information at 2048×2048 resolu-tion. Here is the samples-
![IIM-GAN test image samples](https://user-images.githubusercontent.com/5467074/110726692-30f71280-825d-11eb-821d-5e5eb24b1a46.jpg)

### Test data description
There are 9 EIA samples and 4053 OVI files available to test.
Download link - https://app.box.com/s/q38r66s5x2yk4nf0avz54qhlkbvimzmy

## Train
To train the model, run the train.py Don't forget to pass the argument such upscaling factor, epochs, etc.

## Test
To test a single image run the test_image.py pass the argument such as image name, scale factor, pytorch model, etc.

The loss, score, PSNR, SSIM values are in the statistics folder.

# Thank you very much
