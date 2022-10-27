# Image Fundamentals - Quantization & Interpolation

## Overview
This exercise focuses on quantizing an image at different levels and comparing the results both with and without histogram equalization. Additionally, it involves interpolation methods for upsampling and downsampling.

## Exercise Content
- **1.1.1.** For two cases without and with histogram equalization (uniform histogram), display the quantized image in (4, 8, 16, 32, 64, 128) Levels and its histograms. Also, the optimum mean square error was obtained for each case.

- **1.1.2.** Write a program that can, firstly, downsample the Goldhill image by a factor of 2, with and without using the averaging filter, and also, up-sample the previously downsampled images by a factor of 2, using the pixel replication and bilinear interpolation methods, respectively. 

- **1.1.3.** The initial image consists of eight bits of data for each pixel. Create new images using 5, 4, 3, 2, and 1 bit only for each pixel. 

## Photo Sources
The images used for this exercise can be found in the `data` folder:
- **Elaine Image**: `data/Elaine.bmp`
- **Goldhill Image**: `data/Goldhill.bmp`
- **Barbara Image**: `data/Barbara.bmp`

## Colab Notebook
The full implementation of the exercise, including code and output results, is provided in the [Colab Notebook](https://colab.research.google.com/github/bitua79/computer-vision/blob/main/HW1/Vision_HW1.ipynb). The notebook covers:
- Image quantization for different levels.
- Histogram equalization effects.
- Mean Square Error (MSE) calculations for image quality.
- Downsampling and upsampling with interpolation.

## Instructions to Run
1. Clone this repository and navigate to the folder for this exercise.
2. Open the notebook file (`Vision_HW1.ipynb`) either locally or in Google Colab.
3. Make sure the required images are in the `data` folder, and run the code cells to see the outputs.

## Results and Discussion
The results of the exercises are included in the notebook, with discussions on how image quality changes across different methods.
