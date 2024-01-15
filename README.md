# Handwritten Digit Recognition
######
---------------------------
![Cover](https://cdn-images-1.medium.com/max/800/1*jlxdirCP5Qre1pcoNC-7JQ.png)

# Problem Statement and Data Description
The MNIST dataset contains 70,000 small square 28×28 pixel grayscale training images of handwritten digits from 0 to 9 and 10,000 images for testing. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

Handwritten digit recognition using neural network, trained on `60000` images from `MNIST dataset`.

# Requirements
opencv-python-headless==4.5.3.56

matplotlib==3.4.3

numpy==1.21.2

pillow==7.0.0

bokeh==2.1.1

torch==1.11.0

torchvision==0.12.0

tqdm==4.63.0

ipywidgets==7.7.0

livelossplot==0.5.4

pytest==7.1.1

pandas==1.3.5

seaborn==0.11.2

jupyter==1.0.0

ipykernel==4.10.0

# Accuracy
The model achieved an accuracy over 97.64%. It is trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation. Tested on `10000` images. It's built from scratch using PyTorch.
